---
order: 0
title:
  zh-CN: 基本
  en-US: Basic
---

## zh-CN

默认选中第一项。

## en-US

Default activate first tab.

````jsx
import { Tabs } from 'antd';
const TabPane = Tabs.TabPane;

function callback(key) {
  console.log(key);
}

ReactDOM.render(
  <Tabs defaultActiveKey="3" onChange={callback}>
    <TabPane tab="监控" key="1">Content of Tab Pane 1</TabPane>
    <TabPane tab="测试" key="2">Content of Tab Pane 2</TabPane>
    <TabPane tab="啦啦啦 3" key="3">Content of Tab Pane 3</TabPane>
  </Tabs>
, mountNode);
````
