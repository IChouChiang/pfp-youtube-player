# PFP YouTube Player
播放器网页：<https://ichouchiang.github.io/pfp-youtube-player/>
## 介绍 / Introduction
本播放器可将 360p 至 8K 通常长宽比的视频进行 1:1 像素映射，在分辨率较小的设备上播放高画质视频的局部，观赏视频的细节。  

暂不支持手机 Edge 浏览器。  

在日常播放视频时，如果视频分辨率高于屏幕分辨率，多个视频像素将被压缩到一个物理像素点中；如果视频分辨率低于屏幕分辨率，则一个视频像素会由多个物理像素点显示出来。这两种缩放情况都会导致轻微的失真，影响观看体验。因此，我创建了这个项目，以确保每个视频像素与物理像素一一对应，带来最清晰的视觉效果。

This player enables **1:1 pixel mapping** for videos from **360p to 8K**, allowing you to view high-resolution video details on smaller screens by focusing on parts of the video.  
Note: **Edge browser on mobile** is currently not supported.

During regular video playback, if the video resolution exceeds the screen resolution, multiple video pixels are compressed into a single physical pixel. Conversely, if the video resolution is lower than the screen resolution, a single video pixel is stretched across multiple physical pixels. Both cases result in slight scaling distortions, affecting the viewing experience. This project was created to ensure that every video pixel maps directly to a physical pixel, providing the clearest possible visual experience.

---

## 使用方法 / How to Use

1. **播放视频 / Load Video:**  
   - 在文本框中输入 YouTube 链接，并点击 **Load Video** 按钮载入视频。  
   - 若视频载入后显示“无法播放（Video unavailable）”，请尝试更换链接。  
   
   - Enter a YouTube link into the text box and click **Load Video** to load the video.  
   - If the video shows "Video unavailable," try using a different link.

2. **DPI缩放 / DPI Scaling:**  
   - 若因为 YouTube 切换画质按钮太小，不便于点击或触摸，请使用 **“Zoom & Select / Reset”** 按钮来放大。  
   - 选择好画质后，再次单击此按钮以取消放大。

   - If the YouTube quality switch buttons are too small for comfortable clicking or tapping, use the **“Zoom & Select / Reset”** button to zoom in.  
   - After selecting your desired quality, click the button again to return to the original view.

---

## 补充 / Additional Information

- **支持链接格式 / Supported Link Formats:**  
  - 完整链接 (Full link), 短链接 (Short link), 和嵌入链接 (Embed link)。  
  - **不支持短视频 / Shorts are not supported.**

- **视频无法播放 / Video Unavailable:**  
  - 这通常是由于版权保护导致的。音乐视频或商业制作内容常被禁止嵌入播放。  
   
   - Some videos, such as music videos or commercial content, may be protected by copyright and restricted from being played via embedded players.

- **清晰度限制 / Quality Limit:**  
  - **360p** 是最低支持的分辨率，因为低于此无法切换画质。  
  - 当顶部显示的画质为 **highres** 即为 8K。移动设备通常最高支持 **4K**。
 
  - 360p is the minimum supported resolution, as it's not possible to switch quality levels below this.
  - When the quality displayed at the top is highres, it indicates 8K resolution. On mobile devices, the maximum supported resolution is usually 4K.
