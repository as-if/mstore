WebP Express 0.15.3. Conversion triggered using bulk conversion, 2019-09-24 06:00:59

*WebP Convert 2.1.4*  ignited.
- PHP version: 7.3.1
- Server software: Apache

Stack converter ignited
Destination folder does not exist. Creating folder: [doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/themes/storefront/assets/images/customizer/starter-content/products

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg.webp
- log-call-arguments: true
- converters: (array of 9 items)

The following options have not been explicitly set, so using the following defaults:
- converter-options: (empty array)
- shuffle: false
- preferred-converters: (empty array)
- extra-converters: (empty array)

The following options were supplied and are passed on to the converters in the stack:
- default-quality: 70
- encoding: "auto"
- max-quality: 80
- metadata: "none"
- near-lossless: 60
- quality: "auto"
------------


*Trying: cwebp* 

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg.webp
- default-quality: 70
- encoding: "auto"
- low-memory: true
- log-call-arguments: true
- max-quality: 80
- metadata: "none"
- method: 6
- near-lossless: 60
- quality: "auto"
- use-nice: true
- command-line-options: ""
- try-common-system-paths: true
- try-supplied-binary-for-os: true

The following options have not been explicitly set, so using the following defaults:
- alpha-quality: 85
- auto-filter: false
- preset: "none"
- size-in-percentage: null (not set)
- skip: false
- rel-path-to-precompiled-binaries: *****
------------

Encoding is set to auto - converting to both lossless and lossy and selecting the smallest file

Converting to lossy
Locating cwebp binaries
1 cwebp binaries found in common system locations
Checking if we have a supplied binary for OS: Darwin... We do.
We in fact have 1
A total of 2 cwebp binaries where found
Detecting versions of the cwebp binaries found (and verifying that they can be executed in the process)
Executing: /usr/local/bin/cwebp -version. Result: version: 1.0.3
Executing: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12 -version
Exec failed (the cwebp binary was not found at path: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12)
Trying executing the cwebs found until success. Starting with the ones with highest version number.
Creating command line options for version: 1.0.3
Quality of source is 96. This is higher than max-quality, so using max-quality instead (80)
The near-lossless option ignored for lossy
Trying to convert by executing the following command:
nice /usr/local/bin/cwebp -metadata none -q 80 -alpha_q '85' -m 6 -low_memory '[doc-root]/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg.webp.lossy.webp' 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg.webp.lossy.webp'
File:      [doc-root]/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg
Dimension: 801 x 801
Output:    15798 bytes Y-U-V-All-PSNR 47.58 51.26 50.74   48.45 dB
           (0.20 bpp)
block count:  intra4:        404  (15.53%)
              intra16:      2197  (84.47%)
              skipped:      2107  (81.01%)
bytes used:  header:            223  (1.4%)
             mode-partition:   2701  (17.1%)
 Residuals bytes  |segment 1|segment 2|segment 3|segment 4|  total
  intra4-coeffs:  |   10723 |      42 |      30 |      34 |   10829  (68.5%)
 intra16-coeffs:  |      42 |      14 |      14 |      76 |     146  (0.9%)
  chroma coeffs:  |    1655 |      40 |      36 |     140 |    1871  (11.8%)
    macroblocks:  |      17%|       1%|       1%|      82%|    2601
      quantizer:  |      27 |      26 |      22 |      16 |
   filter level:  |      18 |       5 |      10 |       2 |
------------------+---------+---------+---------+---------+-----------------
 segments total:  |   12420 |      96 |      80 |     250 |   12846  (81.3%)

Success
Reduction: 66% (went from 46 kb to 15 kb)

Converting to lossless
Locating cwebp binaries
1 cwebp binaries found in common system locations
Checking if we have a supplied binary for OS: Darwin... We do.
We in fact have 1
A total of 2 cwebp binaries where found
Detecting versions of the cwebp binaries found (and verifying that they can be executed in the process)
Executing: /usr/local/bin/cwebp -version. Result: version: 1.0.3
Executing: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12 -version
Exec failed (the cwebp binary was not found at path: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12)
Trying executing the cwebs found until success. Starting with the ones with highest version number.
Creating command line options for version: 1.0.3
Trying to convert by executing the following command:
nice /usr/local/bin/cwebp -metadata none -q 80 -alpha_q '85' -near_lossless 60 -m 6 -low_memory '[doc-root]/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg.webp.lossless.webp' 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg.webp.lossless.webp'
File:      [doc-root]/wp-content/themes/storefront/assets/images/customizer/starter-content/products/hoodie-with-logo.jpg
Dimension: 801 x 801
Output:    88590 bytes (1.10 bpp)
Lossless-ARGB compressed size: 88590 bytes
  * Header size: 1785 bytes, image data size: 86779
  * Lossless features used: PREDICTION CROSS-COLOR-TRANSFORM SUBTRACT-GREEN
  * Precision Bits: histogram=5 transform=4 cache=10

Success
Reduction: -89% (went from 46 kb to 87 kb)

Picking lossy
cwebp succeeded :)

Converted image in 734 ms, reducing file size with 66% (went from 46 kb to 15 kb)
