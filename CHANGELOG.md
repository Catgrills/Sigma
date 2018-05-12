# Changelog
All code added/removed/changed will be listed in this changelog.

## 29-03-2018
### Removed
- at line 658-692
``` css
    #watch-card-header.ytd-generic-watch-card {
        background: #E01931 !important;
    }

    ytd-generic-watch-card {
        background: var(--card-bg-2) !important;
        border-bottom-right-radius: 2px !important;
        border-bottom-left-radius: 2px !important;
        box-shadow: 0px 1px 2px rgba(0, 0, 0, .1) !important;
    }

    ytd-artist-watch-card-renderer {
        border-top-right-radius: 2px !important;
        border-top-left-radius: 2px !important;
    }

    ytd-generic-watch-card #watch-card-title.ytd-generic-watch-card,
    ytd-generic-watch-card #related-header * {
        color: #FFF !important;
        font-family: "Roboto Condensed" !important;
        font-size: 10pt !important;
    }

    ytd-generic-watch-card #watch-card-labels.ytd-generic-watch-card  * {
        font-family: "Roboto Condensed" !important;
        font-size: 10pt !important;
    }

    ytd-generic-watch-card  paper-tabs.ytd-generic-watch-card {
        display: none !important;
    }

    ytd-generic-watch-card .video-row.ytd-watch-card-video-list-renderer {
        border-bottom: 1px dotted #000 !important;
    }
```

### Added
- at line 82
``` css
  #button[aria-label="Upload"]
```
- at line 536-538 
``` css
  #filter-group-name.ytd-search-filter-group-renderer {
    border-style: dotted;   
  }

```
- at line 669-706
``` css
  .style-scope.ytd-universal-watch-card-renderer {
      background: var(--card-bg-2) !important;
      border-top-right-radius: 2px !important;
      border-top-left-radius: 2px !important;
  }

  .style-scope.ytd-universal-watch-card-renderer #watch-card-title.yt-simple-endpoint.ytd-watch-card-rich-header-renderer * {
      font-family: "Roboto Condensed" !important;
      font-size: 16pt !important;
  }

  #badge-row.ytd-watch-card-rich-header-renderer * {
      font-family: "Roboto Condensed" !important;
      font-size: 14pt !important;
  }

  .style-scope.ytd-universal-watch-card-renderer #lists {
      background: var(--card-bg-2) !important;
      box-shadow: 0px 1px 2px rgba(0,0,0,.1) !important;
      margin-top: -16px !important;
  }

  .style-scope.ytd-universal-watch-card-renderer ytd-watch-card-compact-video-renderer[is-condensed] {
      border-bottom: 1px dotted #BEBEBE !important;
      padding: 10px 15px 15px 15px !important;
  }

  .style-scope.ytd-universal-watch-card-renderer ytd-watch-card-compact-video-renderer[is-condensed] *,
  #view-all-endpoint.yt-simple-endpoint.ytd-vertical-watch-card-list-renderer {
      color: #FFF !important;
      font-family: "Roboto Condensed", "ぼくたちのゴシック２ボールド", "BM YEONSUNG" !important;
      font-size: 14pt !important;
  }

  #view-all-endpoint.yt-simple-endpoint.ytd-vertical-watch-card-list-renderer {
      border: none !important;
      padding: 0px 15px 20px 15px !important;
  }
```
- at line 1248-1257 
``` css
  #owner-container #button * {
      color: var(--primary-color) !important;
      font-family: "Roboto Condensed" !important;
      font-size: 14pt !important;
      text-transform: capitalize;
  }

  #owner-container .style-scope.ytd-subscribe-button-renderer {
    text-transform: uppercase !important;   
  }

```
- at line 1291-1296
``` css
  #notification-preference-toggle-button,
  #notification-preference-toggle-button * {
      background: transparent !important;
  }

  #notification-preference-toggle-button {
      margin-top: 2px;
  }
```

### Modified
- at line 234
``` css
  .style-scope.ytd-masthead.notification-button-style-type-default yt-icon
```
- at line 530
``` css
  #collapse * {
      color: var(--primary-color);
      font-family: "Roboto Condensed" !important;
      font-size: 15pt !important;
  }
```

## 24-04-2018

### Added 
- at line 181
``` css
  #search-form.ytd-searchbox {
      position: absolute !important;
      top: 12px !important;
      left: 162px !important;
  }
```

### Modified
- at line 173
``` css
  #container.ytd-searchbox
```
- at line 189 
``` css
  font-family: "Roboto Condensed", "ぼくたちのゴシック２ボールド" !important;
```

## 12-05-2018

### Added 
- at line 552
``` css
  .text-wrapper.ytd-video-renderer {
      width: 100% !important;
      max-width: 100% !important;
  }
```
- at line 1950
``` css
  ytd-menu-service-item-renderer:hover,
  paper-listbox.yt-dropdown-menu paper-item.yt-dropdown-menu:hover {
      background: var(--card-bg-2) !important;
  }
```
### Modified
- at line 1190
``` css
  #info #count {
      /*** WATCH INFORMATIONS VIEW ***/
      margin-top: 0px !important;
  }
```
- at line 1942
``` css
  yt-live-chat-message-input-renderer,
  #contents.yt-live-chat-renderer,
  .dropdown-content.style-scope.ytd-popup-container,
  #contentWrapper.iron-dropdown #items,
  paper-listbox.yt-dropdown-menu {
	background: var(--card-bg) !important;
  }
```

