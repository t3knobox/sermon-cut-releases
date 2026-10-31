# Sermon Cut

<p align="center">
  <a href="https://github.com/t3knobox/sermon-cut-releases/releases/latest/download/SermonCut-Setup.exe">
    <img src="https://img.shields.io/badge/Download%20Sermon%20Cut-for%20Windows-2ea44f?style=for-the-badge&logo=windows&logoColor=white" alt="Download Sermon Cut for Windows" height="56">
  </a>
  <br>
  <img src="https://img.shields.io/github/v/release/t3knobox/sermon-cut-releases?label=newest%20version&style=flat-square" alt="Newest version">
</p>

## How to install

1. Click the green **Download** button above.
2. Open the file that downloads (**SermonCut-Setup.exe**).
3. If Windows shows a blue warning, click **More info**, then **Run anyway**.
4. Click through the installer and press **Finish**. Sermon Cut opens.

The first time you use it, it downloads its speech files (about 1.5 GB), so be online for that.

**Updates install themselves:** when a new version is out, an **Update available** button appears inside the app.

---

## About

Sermon Cut turns a Sunday service recording into a finished sermon video.

- Give it the **service recording** and the **sermon PowerPoint**.
- It finds where the sermon starts and ends, and writes out every word that was said.
- It puts each slide on screen at the moment it was shown, and tidies long pauses and "um"s.
- You check everything and change anything you like, then export the video.
- It all runs on your own laptop: no account, and no internet needed after the first setup.

---

## How to use it

### 1. Start a new sermon
1. On the home screen, drag the **recording** (.mp4) and the **sermon slides** (.pptx) into the box. You can also click **Browse** next to each one.
2. If there were worship songs with slides, add the **worship slides** too (optional).
3. Under **Speaker**, choose **Klein** or **Other speaker**.
4. Click **Start edit**.

### 2. The quick check
The app looks through the recording first (a few minutes). Then:
1. If it asks **Where is the projected slide?**, drag the box over the slide on the wall and click **That's the slide**.
2. If it asks **Where does the sermon start and end?**, play to the start and press **Start here**, then to the end and press **End here**, then **Continue**.
3. On **Quick check**, look at the sermon times and the slides it found. If they look right, click **Looks right, write the transcript**.

Writing the transcript takes the longest: roughly 15 to 40 minutes, longer on an older laptop. Keep the laptop **plugged in** and awake. You can leave it running and come back.

### 3. Edit
- The words on the right are everything that was said. **Crossed-out words are cut** and won't be in the video.
- **To cut words:** drag across them, then press **Backspace**.
- **To bring words back:** click a crossed-out word, or select it and press **Backspace**.
- **Undo** and **Redo** are at the top (or Ctrl+Z and Ctrl+Shift+Z).
- Under the video there are two tabs:
  - **Slides to check**: slides the app wasn't sure about. Click a card to go there, then the tick when it looks right.
  - **Suggestions**: cuts suggested by an assistant such as ChatGPT. Click a card to go there, then **Cut it** or **Keep it**.
- To change where the sermon starts or ends, play to that point and click the start or end time under the video.

### 4. Preview
- **Play** with the round button or the Space bar. **10s** and **1m** jump back and forward.
- **Skip cuts** on: you hear it as the final video. Off: you also hear what was cut.
- **Follow** keeps the timeline moving with the video.
- The **eye** button hides the slides in the preview so you can see the speaker. The video always has them.

### 5. Export
1. Click **Export** (top right), choose **720p** or **1080p**, then **Export**.
2. The first time, choose the folder to save in. Each sermon gets its own folder inside it.
3. Exporting takes a few minutes to about 20 minutes. Keep the laptop plugged in.

If there was worship, **Export all** in the side bar also makes the worship video.

### If something goes wrong
- **No slides found, or the wrong slides:** on **Quick check**, click **Use other files** and choose the right PowerPoint.
- **The sermon starts or ends at the wrong time:** on **Quick check**, click **Change**. In the editor, use the start and end times under the video.
- **Something else:** close the app and open it again. Your work is saved as you go. If it keeps happening, send the file **app.log**: press Windows + R, type `%LOCALAPPDATA%\Sermon Cut` and press Enter, and it's in that folder.
