# 🖼️ Universal Image Resizer

Resize images to any popular format for social media, web, print, and more! This is a simple, client-side web application that allows you to quickly resize your images without uploading them to a server.

## ✨ Features

*   **Predefined Sizes**: Quickly select from a wide range of popular dimensions for:
    *   Social Media (Instagram Posts, Facebook Posts, LinkedIn Posts, Pinterest Squares)
    *   Social Media Stories (Instagram, Facebook, TikTok, YouTube Shorts)
    *   Social Media Banners (Facebook Cover, Twitter Header, LinkedIn Banner, YouTube Channel Art)
    *   Profile Pictures (Instagram, Facebook, Twitter, LinkedIn)
    *   Web & Digital (Website Hero, Blog Featured, Banner Ads)
    *   Print & Standard (A4, Business Card, HD & 4K Wallpapers)
*   **Custom Dimensions**: Enter your desired width and height for a custom resize.
*   **Quick Aspect Ratios**: Easily apply common aspect ratios (1:1, 16:9, 4:3, 3:2, 9:16, 2:3) to your custom dimensions.
*   **Image Upload**: 
    *   Drag and drop your image onto the upload area.
    *   Click the "Choose Image" button to select a file from your device.
*   **Supported Formats**: Works with common image formats like PNG, JPG, GIF, WebP, and others supported by the browser.
*   **Live Preview**: See a preview of your original image and the resized version side-by-side.
*   **Download**: Easily download the resized image to your computer.
*   **Client-Side Processing**: All resizing is done in your browser. Your images are not uploaded to any server, ensuring privacy.
*   **Quality & Transparency**: 
    *   Preserves transparency for PNG images.
    *   Maintains aspect ratio with smart padding or cropping (details on this specific behavior might need to be inferred or tested, the UI mentions it).
    *   Aims for high-quality resizing using HTML5 canvas optimization.

## 🚀 How to Use

1.  **Open the Application**: Simply open the `index.html` file in your web browser.
2.  **Choose Your Size**:
    *   **Preset Sizes**: Click on any of the predefined size options from the categories. The selected size will be highlighted and displayed.
    *   **Custom Size**:
        1.  Locate the "⚙️ Custom Size" section.
        2.  Enter your desired `Width` and `Height` in the input fields.
        3.  Optionally, click on a "Quick Ratio" (e.g., 16:9) to automatically calculate one dimension if the other is set, or to set a common aspect ratio.
        4.  Click the "Apply" button next to the custom inputs.
3.  **Upload Your Image**:
    *   Drag your image file and drop it onto the designated "Drop your image here or click to upload" area.
    *   Alternatively, click the "Choose Image" button and select an image file from your computer.
4.  **Preview & Resize**:
    *   Once an image is uploaded and a size is selected, the application will process the image.
    *   A progress bar will indicate the resizing process.
    *   You will see a preview of your "Original Image" and the "Resized Image" along with their dimensions.
5.  **Download the Resized Image**:
    *   Click the "Download Resized Image" button beneath the resized image preview.
    *   The image will be downloaded to your default downloads folder.

## 🛠️ Technical Details

*   The application is built using HTML, CSS, and JavaScript.
*   Image resizing is performed client-side using the HTML5 Canvas API.

## 📂 Project Structure

```
image_resizer/
├── .github/
│   └── workflows/
│       └── static.yml  (For GitHub Pages deployment or CI)
├── index.html          (The main application file)
└── README.md          
```

Enjoy resizing your images with ease!