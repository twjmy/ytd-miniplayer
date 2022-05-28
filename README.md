# YouTube Mini player video hide stylesheet

Self CSS practise

```css
ytd-miniplayer {
    --ytd-miniplayer-height: 2px;
    --ytd-miniplayer-card-height: 65px;
}
ytd-miniplayer[animate-miniplayer]:not([expanded]) {
    height: 450px;
}
.ytd-miniplayer video.video-stream.html5-main-video {
    display: none;
    height: 0!important;
}
.ytd-miniplayer .ytp-tooltip.ytp-bottom.ytp-preview,
.ytd-miniplayer .ytp-preview:not(.ytp-text-detail) * {
    top: unset!important;
}
.ytp-miniplayer-expand-watch-page-button,
#info-bar.ytd-miniplayer .expander.ytd-miniplayer {
    display: none;
}
```

## Screenshort
### Collapse

![image](https://user-images.githubusercontent.com/32490451/170841912-4b92e81e-0b78-4c84-a613-0b4803d9dc2c.png)

### Expand

![image](https://user-images.githubusercontent.com/32490451/170841973-db4e2070-8306-4a68-a427-c12c1fe75480.png)
