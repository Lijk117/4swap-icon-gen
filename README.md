# 4swap Icons generator

Generate icons and directory structure according to the [contribute guideline](https://github.com/MixinNetwork/asset-profile)


## Usage

```
$ ./4swap-icon-gen -config keystore.json -a0 NEW_ASSET_ID -a1 54c61a72-b982-4034-a556-0d99e3c21e39 -a2 a31e847e-ca87-3162-b4d1-322bc552e831
```

Using custom icon files:

```
$ ./4swap-icon-gen -config keystore.json -a0 NEW_ASSET_ID -a1 54c61a72-b982-4034-a556-0d99e3c21e39 -a2 a31e847e-ca87-3162-b4d1-322bc552e831 -ic1 ./btc.png -ic2 ./dot.png
```

Using custom colors:

```
$ ./4swap-icon-gen -config keystore.json -a0 NEW_ASSET_ID -a1 54c61a72-b982-4034-a556-0d99e3c21e39 -a2 a31e847e-ca87-3162-b4d1-322bc552e831 -c1 "#F7931B" -c2 "#000000"
```

Using custom output path:

```
$ ./4swap-icon-gen -config keystore.json -a0 NEW_ASSET_ID -a1 54c61a72-b982-4034-a556-0d99e3c21e39 -a2 a31e847e-ca87-3162-b4d1-322bc552e831 -o YOUR_OUTPUT_PATH
```