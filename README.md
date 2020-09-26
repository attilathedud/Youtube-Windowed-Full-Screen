# Youtube-Windowed-Full-Screen
A Chrome extension that forces Youtube videos to fill the entire browser window when in theater mode. 

![promo](promo.png?raw=true)

This was written not as a stable product but instead to demonstrate how easy it is to do. 

## Technique
Youtube changes its layout constantly. For when this inevitably breaks, here is the technique:
1. Set the search bar's display to none.
2. The page's container has a margin for the search bar. Set that margin to 0.
3. Set the theater's container max-height to 100vh.
4. Set the left on the video to 0. Set the width to 100% and the height to 100vh.
