<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Frame](./puppeteer.frame.md) &gt; [$$](./puppeteer.frame.__.md)

## Frame.$$() method

This runs `document.querySelectorAll` in the frame and returns the result.

<b>Signature:</b>

```typescript
$$<T extends Element = Element>(selector: string): Promise<Array<ElementHandle<T>>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  selector | string | a selector to search for |

<b>Returns:</b>

Promise&lt;Array&lt;[ElementHandle](./puppeteer.elementhandle.md)&lt;T&gt;&gt;&gt;

An array of element handles pointing to the found frame elements.
