# vue-marked-editor

[docs](https://blog.yuanxinfeng.xyz/article?id=5ceb46b89fc397692b12b37c)

## Install

```shell
$ npm install --save vue-marked-editor
```

## Quick Start

```javascript
import Vue from "vue";
import vueMarkedEditor from "vue-marked-editor";
import "vue-marked-editor/vue-marked-editor.css";

Vue.use(vueMarkedEditor);
```

```html
<y-markdown
  ref="markdown"
  :mdValuesP="value"
  :fullPageStatusP="false"
  :editStatusP="true"
  :previewStatusP="true"
  :navStatusP="true"
  :icoStatusP="true"
  @childevent="childEventHandler"
  @imgAdd="imgAdd"
  @delImage="delIMage"
></y-markdown>
```

## LICENSE

[MIT](LICENSE)

## GITHUB

[vue-marked-editor](https://github.com/yuanxinfeng/vue-marked-editor)
Welcome to star !!!
