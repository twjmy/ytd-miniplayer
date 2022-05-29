# YouTube Mini player video hide stylesheet

[![badge-cc-by-nc-sa][badge-cc-by-nc-sa]][url-cc-by-nc-sa]

[badge-cc-by-nc-sa]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[url-cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0

Self CSS practise

```css
ytd-miniplayer {
    --ytd-miniplayer-height: 2px;
}
ytd-miniplayer[animate-miniplayer]:not([expanded]) {
    height: 453px;
}
.ytd-miniplayer .ytp-tooltip.ytp-bottom.ytp-preview,
.ytd-miniplayer .ytp-preview:not(.ytp-text-detail) * {
    top: unset!important;
}
.ytp-miniplayer-expand-watch-page-button,
#info-bar.ytd-miniplayer .expander.ytd-miniplayer,
.ytd-miniplayer video.video-stream.html5-main-video {
    display: none;
}
```

## Screenshort

+ Pause  
![image](https://user-images.githubusercontent.com/32490451/170844182-8f4c4933-6f73-4dcc-87aa-e9a677bf33be.png)
+ Tooltip/CC  
![image](https://user-images.githubusercontent.com/32490451/170843307-cb9945a5-ec23-497c-a25f-7592648f6db7.png)
+ Expand  
![image](https://user-images.githubusercontent.com/32490451/170841973-db4e2070-8306-4a68-a427-c12c1fe75480.png)
