


core包中
index.js---导出 startApp  setupApp  preloadApp  destroyApp
iframe.js---iframeGenerator，js沙箱负责创建和主应用同源的iframe
sanbox.js---Wujie类，基于 Proxy和iframe 实现的沙箱
shadow.js---处理wujie webComponent相关内容
proxy.js---代理window、document、location
event.js---eventBus 事件中心
sync.js---路由同步相关



