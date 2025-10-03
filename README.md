# heroku-buildpack-transcrypt

Decrypt your transcrypt-encrypted files on deploy.

# Usage

Assuming you have a repo that you had set up with transcrypt using aes-256-cbc and encrypted some files...

```bash
heroku config:set TRANSCRYPT_PASS="my-password"
heroku buildpacks:add --index 1 https://github.com/fwolff/heroku-buildpack-transcrypt
```

<3
