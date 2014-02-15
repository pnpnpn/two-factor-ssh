two_factor_ssh
==============

Two-Factor SSH Authentication with OTP, e.g. [Google Authenticator](http://code.google.com/p/google-authenticator/)

After copying `two_factor_ssh` to your `/usr/bin/`. Add the following line to your `authorized_keys`:

	command="/usr/bin/two_factor_ssh 4rr7kc47sc5a2fgt" ssh-dsa AAA...zzz me@example.com

Code taken from: <https://moocode.com/posts/5-simple-two-factor-ssh-authentication>

