# Bank logos
This directory contains static bank logo images.
The file names should not include the bank name and/or id.

Proposition of generating names for new bank logo file (on Linux):

```sh
echo "l_"$(uuidgen | xxd -r -p  | base64 -w0 | basenc --base64url | tr -d '=')
```

It will generate new uuid and encode it as `base64url`.
You should add file extension to the end of the generated filename.

The absolute address of the bank logo file must be added to ramp backend database.
