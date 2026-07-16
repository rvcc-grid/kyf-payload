# Know Your Files: Payload — READ ME FIRST

Welcome back, recruit. This mission is about weight.

Every kilobyte a web page carries costs the visitor
time. Today you will fetch two magnificent, enormous
photos from the NASA archive, feel what they do to a
page, weigh them with a real developer tool, and trim
them to flight weight.

You know the drill by now: open this file in VS Code
and hit Markdown preview (Shift+Cmd+V on Mac,
Shift+Ctrl+V on Windows).

## Phase 1 — fetch the cargo

Download BOTH originals. On each page, use the
Download button and choose the LARGEST size offered.

1. Artemis I Launch
   https://images.nasa.gov/details/NHQ202211160028
   Save it into the images folder as: rocket-launch.jpg

2. Curiosity at Glen Etive (the Mars selfie)
   https://images.nasa.gov/details/PIA23378
   Save it into the images folder as: mars-selfie.jpg

Exact names matter — you learned this on Liftoff.
The page's cargo manifest will tell you if it can't
find them.

## Phase 2 — weigh it

1. Right-click index.html → Open in Integrated Browser
   (or use any browser).
2. Open DevTools and click the Network tab.
3. Check "Disable cache" in the Network tab.
4. Reload the page.
5. Read the summary bar at the bottom. Write down two
   numbers: how many MB transferred, and the finish
   time. That is what every visitor would pay.

## Phase 3 — trim it

1. Go to https://squoosh.app in your browser.
2. Drop in one of your downloaded photos.
3. On the right side: set Resize ON and width to 1200.
4. Keep the format as MozJPEG and watch the size
   readout at the bottom — aim for 300 KB or less.
5. Slide the quality slider and watch the image with
   your own eyes. Find the spot where the file is small
   but the photo still looks good.
6. Export (the download button), then move the exported
   file into images/ replacing the old one — same name.
7. Repeat for the other photo.
8. Weigh again (Phase 2). Compare your numbers.

The cargo manifest on the page goes green when both
photos are at flight weight.

## Phase 4 — push

ONLY when the manifest says "Cleared for launch":
commit and push. The pushed repo is your submission.

## Rules

- Do NOT commit or push the original downloads. The
  originals are cargo, not luggage — they never fly.
  Push only after both photos are trimmed.
- Do NOT rename index.html.
- Keep this README where it is.

Fly light. 🚀
