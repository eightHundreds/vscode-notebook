# NoteBook

a markdown notebook plugin


## Feature

### paste text or image

![](images/docs/paste.gif)

You can custom keyboard shortcut for this command ,eg:
``` JSON
[
    {
        "key": "cmd+v",
        "command": "-editor.action.clipboardCopyAction",
        "when": "editorTextFocus && editorLangId == markdown",
    },
    {
        "key": "cmd+v",
        "command": "notebook.paste",
        "when": "editorTextFocus && editorLangId == markdown",
    }
]
```

#### link paste enhanced

auto get title of link

![](images/docs/linkCompletion.gif)


### Markdown Preview Enhanced Integration

automatically configure [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) by setting `notebook.markdownPreviewEnhancedIntegration` (default:false)

![](images/docs/integrationMdEnhance.gif)


### Notebook Link

![](images/docs/noteLink.gif)

### Tag tree view

![](images/docs/tag.gif)

### Typora Integration

(only work for mac os)

![](images/docs/typora.png)


### draw.io Integration (beta)

![](images/docs/drawio.gif)

configuration

- `notebook.drawIoSite` (default:http://draw.io)
  - 国内可以用码云的pages服务部署drawio，这里有一个部署好的 `http://recodingstupid.gitee.io/drawio/`
- `notebook.drawIoLang` (English is default)
  - `zh` 是中文

## TODO 

- [x] notebook link
- [x] support window
- [x] save and commit command  
- [x] tag
- [x] drawio
- [ ] mindmap 
