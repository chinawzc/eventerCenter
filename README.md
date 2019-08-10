# eventerCenter
pub-sub

引入
> import EventCenter from './EventCenter'

## API

> on
- 添加一个事件监听
- handler优化了下，只能传函数，省的传对象造成不可控

``
eventCenter.on(type, handler)
``

> once
- 添加一个只能触发一次的事件监听

``
eventCenter.once(type, handler)
``

> emit
- 触发事件

``
eventCenter.emit(type, ...params)
``

> off
- 取消一个事件监听

``
eventCenter.off(type, handler)
``

> clear
- 取消所有监听

``
eventCenter.clear()
``
