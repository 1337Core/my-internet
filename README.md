# my-internet

My custom CSS for websites I visit the most. Click on the preview to view the file or visit the repo.

[Browse the repository](https://github.com/sameerasw/my-internet) (More website themes available)

[Visit my website](https://www.sameerasw.com)

[How to get transparency in Zen](https://sameerasw.notion.site/Zen-Transparency-1939c6099d4080468f02cf05ae50e827?pvs=4)

<a href="https://star-history.com/#sameerasw/my-internet&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=sameerasw/my-internet&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=sameerasw/my-internet&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=sameerasw/my-internet&type=Date" />
 </picture>
</a>

## Contributing styles
- You can use the [example.com.css](https://github.com/sameerasw/my-internet/raw/refs/heads/main/websites/example.com.css) as a starter for most websites.
- Make sure the file is named in the correct format [website domain].css (google.com.css and docs.google.com.css are 2 styles which are not merged)
- Please respect auto theming for day and night themes. If the website does not have a dark theme, account for dark reader.
- Do not use wildcards such as applying transparency for all div elements since that is handled with force theming in the addon.
- Every property should include `!important` to make sure it gets applied.
- Do NOT leave commented out code.
- Add propper comments for each section of a feature at the beginning with a clear but compact description.
- Each comment of the same file should have a unique domain specific identified prefix (yt- ytm- gh- ...) which will help the browser to separately apply themes.
  
  ```
    /* yt-transparency */
    :root{
      --colorBgApp: transparent !important;
    }

    /*  yt-no footer */
    footer.app-footer {
      display: none !important;
    }
  ```
  
- Once comitted to the repository, github actions will parse the css file and update/ generate the [styles.js](https://github.com/sameerasw/my-internet/blob/main/styles.json) and then will be deployed to the github pages allowing the add-on to fetch from it.
- Thank you <3


---
## userChrome.css - my Zen browser styling
[![CleanShot 2025-02-11 at 11  04 22@2x Large](https://github.com/user-attachments/assets/141ba655-8af3-4099-b2a9-26d3e33a5d2d)](https://github.com/sameerasw/my-internet/blob/main/userChrome.css)
---

### youtube.com
[![CleanShot 2025-02-08 at 5  55 02@2x Large](https://github.com/user-attachments/assets/4b43abc8-0c83-4224-8fe4-c361319c5be6)](https://github.com/sameerasw/my-internet/blob/main/youtube.com.css)

### aistudio.google.com
[![CleanShot 2025-02-08 at 5  19 00@2x Large](https://github.com/user-attachments/assets/cc9fa133-0bbc-464f-a291-fbc450178d6c)](https://github.com/sameerasw/my-internet/blob/main/aistudio.google.com.css)

### chat.openai.com
[![CleanShot 2025-02-08 at 5  19 24@2x Large](https://github.com/user-attachments/assets/f6a83b6c-d2ac-4647-8dee-ed9c0dd511f7)](https://github.com/sameerasw/my-internet/blob/main/chat.openai.com.css)

### discord.com
[![CleanShot 2025-02-08 at 5  20 15@2x Large](https://github.com/user-attachments/assets/60310fd6-bd7d-41cf-8d51-97ed94f644f2)](https://github.com/sameerasw/my-internet/blob/main/discord.com.css)

### facebook.com
[![CleanShot 2025-02-08 at 5  21 38@2x Large](https://github.com/user-attachments/assets/2c74bbd2-34f8-4bee-887f-f74ccf6a2529)](https://github.com/sameerasw/my-internet/blob/main/facebook.com.css)

### gemini.com
[![CleanShot 2025-02-08 at 5  27 10@2x Large](https://github.com/user-attachments/assets/c6d44454-a0f7-4669-9856-e9ea6ffc41db)](https://github.com/sameerasw/my-internet/blob/main/gemini.google.com.css)

### github.com
[![CleanShot 2025-02-08 at 5  27 29@2x Large](https://github.com/user-attachments/assets/4868141b-92b7-496d-8b35-dfa36f8c550e)](https://github.com/sameerasw/my-internet/blob/main/github.com.css)

### google.com
[![CleanShot 2025-02-08 at 5  27 50@2x Large](https://github.com/user-attachments/assets/504c714c-e063-4807-8f20-432e507a5d91)](https://github.com/sameerasw/my-internet/blob/main/google.com.css)

### instagram.com
[![CleanShot 2025-02-08 at 5  38 45@2x Large](https://github.com/user-attachments/assets/bec55de7-8e3c-4a54-9d53-2e1d777e3637)](https://github.com/sameerasw/my-internet/blob/main/instagram.com.css)

### monkeytype.com
[![CleanShot 2025-02-08 at 5  45 58@2x Large](https://github.com/user-attachments/assets/3241d584-1f4c-4f5a-97d7-d4555bc81f37)](https://github.com/sameerasw/my-internet/blob/main/monkeytype.com.css)

### music.youtube.com
[![CleanShot 2025-02-08 at 5  46 47@2x Large](https://github.com/user-attachments/assets/4aa1683c-29a6-4b50-b5d3-669fbca74952)](https://github.com/sameerasw/my-internet/blob/main/music.youtube.com.css)

### notion.so
[![CleanShot 2025-02-08 at 5  48 05@2x Large](https://github.com/user-attachments/assets/0d0b1eac-9950-4a5d-8274-1e44d494a821)](https://github.com/sameerasw/my-internet/blob/main/notion.so.css)

### pexels.com
[![CleanShot 2025-02-08 at 5  48 38@2x Large](https://github.com/user-attachments/assets/4a88d0e8-0395-4d55-a4e5-5f10f9eddf0c)](https://github.com/sameerasw/my-internet/blob/main/pexels.com.css)

### pinterest.com
[![CleanShot 2025-02-08 at 5  49 06@2x Large](https://github.com/user-attachments/assets/55e468a4-11da-40d6-8301-109fdebf46f7)](https://github.com/sameerasw/my-internet/blob/main/pinterest.com.css)

### reddit.com
[![CleanShot 2025-02-08 at 5  50 17@2x Large](https://github.com/user-attachments/assets/b1e34f88-6dca-4544-b2fd-64841aa7101c)](https://github.com/sameerasw/my-internet/blob/main/reddit.com.css)

### sourceforge.net
[![CleanShot 2025-02-08 at 5  51 00@2x Large](https://github.com/user-attachments/assets/cc927d3d-9021-4c13-a3c9-ba49934024e8)](https://github.com/sameerasw/my-internet/blob/main/sourceforge.net.css)

### speedtest.net
[![CleanShot 2025-02-08 at 5  51 27@2x Large](https://github.com/user-attachments/assets/408b00f8-5366-46da-bacb-94adf0a8062a)](https://github.com/sameerasw/my-internet/blob/main/speedtest.net.css)

### twitch.tv
[![CleanShot 2025-02-08 at 5  52 15@2x Large](https://github.com/user-attachments/assets/2c73c502-0c24-4e6f-9b81-fe52c61ebe96)](https://github.com/sameerasw/my-internet/blob/main/twitch.tv.css)

### unsplash.com
[![CleanShot 2025-02-08 at 5  52 55@2x Large](https://github.com/user-attachments/assets/d58db62b-0db2-4e72-af19-29f2742ae4b4)](https://github.com/sameerasw/my-internet/blob/main/unsplash.com.css)
