# Store Image file into localStorage

To store image file in client side environment, there are some storage options to handle it. This experiment use localStorage to store the image file as DataURL format.

[browser-storage.html](browser-storage.html) demostrate how to store image file into browser localStorage after choose a image file. And load image file from localStorage when initializing the page.

![load image from input file](./img/load-from-input-file.jpg)

![load image from localStorage](./img/load-from-localstorage.jpg)

[file-reader.html](./file-reader.html) use FileReader API: readAsDataURL, readAsArrayBuffer, readAsBinaryString, readAsText to compare loaded file size in different format.

![compare file size in different format](./img/filereader.jpg)