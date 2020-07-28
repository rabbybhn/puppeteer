<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Network](./puppeteer.protocol.network.md) &gt; [LoadingFinishedEvent](./puppeteer.protocol.network.loadingfinishedevent.md)

## Protocol.Network.LoadingFinishedEvent interface

Fired when HTTP request has finished loading.

<b>Signature:</b>

```typescript
export interface LoadingFinishedEvent 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [encodedDataLength](./puppeteer.protocol.network.loadingfinishedevent.encodeddatalength.md) | number | Total number of bytes received for this request. |
|  [requestId](./puppeteer.protocol.network.loadingfinishedevent.requestid.md) | [RequestId](./puppeteer.protocol.network.requestid.md) | Request identifier. |
|  [shouldReportCorbBlocking](./puppeteer.protocol.network.loadingfinishedevent.shouldreportcorbblocking.md) | boolean | Set when 1) response was blocked by Cross-Origin Read Blocking and also 2) this needs to be reported to the DevTools console. |
|  [timestamp](./puppeteer.protocol.network.loadingfinishedevent.timestamp.md) | [MonotonicTime](./puppeteer.protocol.network.monotonictime.md) | Timestamp. |
