---
hero:
  title: Site Name
  desc: dumi site app example
  actions:
    - text: Getting Started
      link: /getting-started
features:
  - icon: https://gw.alipayobjects.com/zos/bmw-prod/881dc458-f20b-407b-947a-95104b5ec82b/k79dm8ih_w144_h144.png
    title: Feature 1
    desc: Balabala
  - icon: https://gw.alipayobjects.com/zos/bmw-prod/d60657df-0822-4631-9d7c-e7a869c2f21c/k79dmz3q_w126_h126.png
    title: Feature 2
    desc: Balabala
  - icon: https://gw.alipayobjects.com/zos/bmw-prod/d1ee0c6f-5aed-4a45-a507-339a4bfe076c/k7bjsocq_w144_h144.png
    title: Feature 3
    desc: Balabala
footer: Open-source MIT Licensed | Copyright © 2020<br />Powered by [dumi](https://d.umijs.org)
---

## 游乐场

瞎写写


```jsx
async function generateNpmDepTree(package) {
  const unpkgHost = 'http://unpkg.zhimg.com';
  const data = {};
  
  fetch(`${unpkgHost}/${package}/package.json`)
    .then(response => response.json())
}

generateNpmDepTree('mime-types');

export default () => <div>分析并获取 node module 依赖树</div>
```