# EditorJS Stretch Tune
- added tunes to stretch block on the full width/screen
At the moment no additional options is supported

**Install**
`yarn add https://github.com/everzel/editorjs-big-head-tune.git#main`

**Connect**
```js
import BigHeadTune from '@everzel/editorjs-big-head-tune'
//...
new EditorJS({
    tools: {
        bigHeadTune: BigHeadTune,
        // apply for specific content block
        paragraph: {
            class: Paragraph,
            tunes: ['bigHeadTune'],
        },
        // or for any block
        tunes: ['bigHeadTune']
    },
})
```
