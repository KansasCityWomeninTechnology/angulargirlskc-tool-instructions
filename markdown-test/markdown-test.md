# Markdown Test

## Markdown

Use normal markdown such as headers, images \(inline and not\), links, ordered and ordered lists, code snippets, tables, quote

### Link to another file

{% page-ref page="../browser/google-chrome.md" %}

## Special Features

### GFM

Some GFM \(Github flavor markdown\) such as tasklist

* [ ] Do this thing
* [ ] And another thing
* [x] This is done

### Add filenames to code snippets

{% code-tabs %}
{% code-tabs-item title="some-file.ts" %}
```typescript
class MyClass {
   constructor(private _name: string) {}
   
   public sayHello() : void {
      alert(`Hello ${this._name}!`);
   }
}
```
{% endcode-tabs-item %}
{% endcode-tabs %}

### Hints \(and Admonishments\)

{% hint style="success" %}
This is success
{% endhint %}

{% hint style="info" %}
This is info
{% endhint %}

{% hint style="warning" %}
This is warning
{% endhint %}

{% hint style="danger" %}
This is danger
{% endhint %}

{% hint style="info" %}
### Markdown inside hints work too
{% endhint %}

### Tabs

{% tabs %}
{% tab title="First Tab" %}
> Sometimes you need to install deps
{% endtab %}

{% tab title="Second Tab" %}
```text
npm i
```
{% endtab %}
{% endtabs %}

### Embed Video

{% embed url="https://vimeo.com/250067069" %}

### Embed CodePen

{% embed url="https://codepen.io/CodingCocktailsKC/pen/EzyyXB" %}

### API

{% api-method method="get" host="" path="" %}
{% api-method-summary %}
Get me cake
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

## New Thing
Here is a code snippet
```bash
rm -rf node_modules
npm install
```
