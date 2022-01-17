---
order: 10
title:
  zh-CN: 额外的页脚
  en-US: Extra Footer
---

## zh-CN

在浮层中加入额外的页脚，以满足某些定制信息的需求。

## en-US

Render extra footer in panel for customized requirements.

```jsx
import { DatePicker, Space } from 'antd';

const { RangePicker } = DatePicker;

ReactDOM.render(
  <Space direction="vertical" size={12}>
    <DatePicker renderExtraFooter={() => '离线数据已覆盖至1月15号，16、17号为实时数据'} />
    <DatePicker renderExtraFooter={() => '离线数据已覆盖至1月15号，16、17号为实时数据'} showTime />
    <RangePicker renderExtraFooter={() => '离线数据已覆盖至1月15号，16、17号为实时数据'} />
    <RangePicker renderExtraFooter={() => '离线数据已覆盖至1月15号，16、17号为实时数据'} showTime />
    <DatePicker renderExtraFooter={() => '离线数据已覆盖至1月15号，16、17号为实时数据'} picker="month" />
  </Space>,
  mountNode,
);
```
