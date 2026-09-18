
```
            _                    _     __  __       
     /\    | |                  | |   |  \/  |      
    /  \   | |__    ___   _   _ | |_  | \  / |  ___ 
   / /\ \  | '_ \  / _ \ | | | || __| | |\/| | / _ \
  / ____ \ | |_) || (_) || |_| || |_  | |  | ||  __/
 /_/    \_\|_.__/  \___/  \__,_| \__| |_|  |_| \___|
                                                    
```

Hey, it's me, Ruochen Jia, nicknamed `gitarmi` in many social media and games.

I'm a casual developer who spends most of the free time messing with the keyboard, working on non sense projects, even though it's a complete waste of time.

I prefer to be anonymous, so please don't disturb me on social media, as I don't check them often.

I dream one day I'll make a successful project with over 100k stars and 1000k contributors.



⁠

<b>My most favorite language</b>
```brainfuck
>>,[>>,]<<[
[<<]>>>>[
<<[>+<<+>-]
>>[>+<<<<[->]>[<]>>-]
<<<[[-]>>[>+<-]>>[<<<+>>>-]]
>>[[<+>-]>>]<
]<<[>>+<<-]<<
]>>>>[.>>]
```

<b>My least favorite language</b>
```python
import os;

# haha I like c-style semicolon in python
# even though it's not quite a good practice

msg = "Hello World\r\n";
os.write(1, msg.encode());
```

<b>The language I use the most</b>
```javascript
"don't use strict";

with (window.self.frames.globalThis) {
	const data = new ImageData(4096, 4096, { colorSpace: "srgb", pixelFormat: "rgba-unorm8" });
	const buffer = data.data;
	const length = buffer.length;
	const pxCount = 4096 * 4096;

	let off = 0;

	for (let i = 0; i < pxCount; i++) {
		buffer[off++] = i & 0xff;
		buffer[off++] = (i >> 8) & 0xff;
		buffer[off++] = (i >> 16) & 0xff;
		buffer[off++] = 0xff; // so annoying, why can't javascript support 24 bit color
	}

	const bmp = await createImageBitmap(data, {
		imageOrientation: "none",
		colorSpaceConversion: "none"
	});

	const canvas = new OffscreenCanvas(4096, 4096);
	canvas.getContext("bitmaprenderer", { alpna: false }).transferFromImageBitmap(bmp);
	bmp.close();

	const k = document.createElement("a");
	k.download = "image.png";
	k.target = "_blank";
	k.href = URL.createObjectURL(await canvas.convertToBlob({ type: "image/png", quality: 100 }));;
	k.click();
}
```

<b>My personal website</b>

https://unbioctium.com

(still under development)
