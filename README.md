# qubes-otp

```
sudo qubes-dom0-update google-authenticator
Y y n y | google-authenticator

#top of /etc/pam.d/xscreensaver
auth required pam_google_authenticator.so

#comment-out `auth include system-auth`
# as alternative: ooath-toolkit
```
