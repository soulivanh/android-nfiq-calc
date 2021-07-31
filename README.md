# android-nfiq-calc
Android SDK that is used to calculate the NFIQ of a captured fingerprint image. 
Project is an Android (Kotlin) implementation of a C-based NFIQ calculator

## Usage
```kotlin
NFIQUtil.calculateNFIQUsingBitmap(context: Context, bitmap: Bitmap)
```
or

```kotlin
NFIQUtil.calculateNFIQUsingRawBytes(rawBytes: ByteArray, imageWidth: Int, imageHeight: Int)

```
