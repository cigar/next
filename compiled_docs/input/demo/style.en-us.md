{"title":"Custom Style","meta":{"title":"Custom Style","description":"\n<p>Custom style can be set using  param <code>style</code>.</p>\n","order":"11"},"codes":{"jsx":"import { Input } from '@alifd/next';\n\nReactDOM.render(\n    <div>\n        <Input placeholder=\"width:400\" style={{width: 400}} aria-label=\"style width 400\" /><br/><br/>\n\n        <Input\n            addonTextBefore=\"http://\"\n            addonTextAfter=\".com\"\n            size=\"medium\"\n            value=\"alibaba\"\n            style={{width: 400}} aria-label=\"style width 400\" /><br/><br/>\n\n        <Input\n            placeholder=\"medium\"\n            maxLength={10}\n            hasLimitHint\n            style={{width: 400}} aria-label=\"style width 400\" /><br/><br/>\n\n        <Input\n            placeholder=\"medium\"\n            hasClear maxLength={10}\n            hasLimitHint style={{width: 400}}\n            className=\"my-input-class\"\n            state=\"success\"\n            aria-label=\"style width 400\" /><br/><br/>\n\n        <Input placeholder=\"className\" className=\"my-input-class\" aria-label=\"custom my input class\" />\n        <Input htmlType=\"hidden\" aria-label=\"hidden input\" />\n    </div>\n    , mountNode);\n","css":"body .my-input-class {\n    width:500px;\n}\n"},"body":"\n````jsx\nimport { Input } from '@alifd/next';\n\nReactDOM.render(\n    <div>\n        <Input placeholder=\"width:400\" style={{width: 400}} aria-label=\"style width 400\" /><br/><br/>\n\n        <Input\n            addonTextBefore=\"http://\"\n            addonTextAfter=\".com\"\n            size=\"medium\"\n            value=\"alibaba\"\n            style={{width: 400}} aria-label=\"style width 400\" /><br/><br/>\n\n        <Input\n            placeholder=\"medium\"\n            maxLength={10}\n            hasLimitHint\n            style={{width: 400}} aria-label=\"style width 400\" /><br/><br/>\n\n        <Input\n            placeholder=\"medium\"\n            hasClear maxLength={10}\n            hasLimitHint style={{width: 400}}\n            className=\"my-input-class\"\n            state=\"success\"\n            aria-label=\"style width 400\" /><br/><br/>\n\n        <Input placeholder=\"className\" className=\"my-input-class\" aria-label=\"custom my input class\" />\n        <Input htmlType=\"hidden\" aria-label=\"hidden input\" />\n    </div>\n    , mountNode);\n````\n\n````css\nbody .my-input-class {\n    width:500px;\n}\n````","html":"<script>(function(){\"use strict\";\n\nvar _next = require(\"@alifd/next\");\n\nReactDOM.render(React.createElement(\n    \"div\",\n    null,\n    React.createElement(_next.Input, { placeholder: \"width:400\", style: { width: 400 }, \"aria-label\": \"style width 400\" }),\n    React.createElement(\"br\", null),\n    React.createElement(\"br\", null),\n    React.createElement(_next.Input, {\n        addonTextBefore: \"http://\",\n        addonTextAfter: \".com\",\n        size: \"medium\",\n        value: \"alibaba\",\n        style: { width: 400 }, \"aria-label\": \"style width 400\" }),\n    React.createElement(\"br\", null),\n    React.createElement(\"br\", null),\n    React.createElement(_next.Input, {\n        placeholder: \"medium\",\n        maxLength: 10,\n        hasLimitHint: true,\n        style: { width: 400 }, \"aria-label\": \"style width 400\" }),\n    React.createElement(\"br\", null),\n    React.createElement(\"br\", null),\n    React.createElement(_next.Input, {\n        placeholder: \"medium\",\n        hasClear: true, maxLength: 10,\n        hasLimitHint: true, style: { width: 400 },\n        className: \"my-input-class\",\n        state: \"success\",\n        \"aria-label\": \"style width 400\" }),\n    React.createElement(\"br\", null),\n    React.createElement(\"br\", null),\n    React.createElement(_next.Input, { placeholder: \"className\", className: \"my-input-class\", \"aria-label\": \"custom my input class\" }),\n    React.createElement(_next.Input, { htmlType: \"hidden\", \"aria-label\": \"hidden input\" })\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Input <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span>\n    <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Input</span> <span class=\"token attr-name\">placeholder</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>width:400<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">{</span>width<span class=\"token punctuation\">:</span> <span class=\"token number\">400</span><span class=\"token punctuation\">}</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">aria-label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>style width 400<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span><span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span><span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Input</span>\n            <span class=\"token attr-name\">addonTextBefore</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>http://<span class=\"token punctuation\">\"</span></span>\n            <span class=\"token attr-name\">addonTextAfter</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>.com<span class=\"token punctuation\">\"</span></span>\n            <span class=\"token attr-name\">size</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>medium<span class=\"token punctuation\">\"</span></span>\n            <span class=\"token attr-name\">value</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>alibaba<span class=\"token punctuation\">\"</span></span>\n            <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">{</span>width<span class=\"token punctuation\">:</span> <span class=\"token number\">400</span><span class=\"token punctuation\">}</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">aria-label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>style width 400<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span><span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span><span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Input</span>\n            <span class=\"token attr-name\">placeholder</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>medium<span class=\"token punctuation\">\"</span></span>\n            <span class=\"token attr-name\">maxLength</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token number\">10</span><span class=\"token punctuation\">}</span></span>\n            <span class=\"token attr-name\">hasLimitHint</span>\n            <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">{</span>width<span class=\"token punctuation\">:</span> <span class=\"token number\">400</span><span class=\"token punctuation\">}</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">aria-label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>style width 400<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span><span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span><span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Input</span>\n            <span class=\"token attr-name\">placeholder</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>medium<span class=\"token punctuation\">\"</span></span>\n            <span class=\"token attr-name\">hasClear</span> <span class=\"token attr-name\">maxLength</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token number\">10</span><span class=\"token punctuation\">}</span></span>\n            <span class=\"token attr-name\">hasLimitHint</span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">{</span>width<span class=\"token punctuation\">:</span> <span class=\"token number\">400</span><span class=\"token punctuation\">}</span><span class=\"token punctuation\">}</span></span>\n            <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>my-input-class<span class=\"token punctuation\">\"</span></span>\n            <span class=\"token attr-name\">state</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>success<span class=\"token punctuation\">\"</span></span>\n            <span class=\"token attr-name\">aria-label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>style width 400<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span><span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span><span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Input</span> <span class=\"token attr-name\">placeholder</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>className<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>my-input-class<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">aria-label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>custom my input class<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Input</span> <span class=\"token attr-name\">htmlType</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>hidden<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">aria-label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>hidden input<span class=\"token punctuation\">\"</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span>\n    <span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div><style type=\"text/css\">body .my-input-class {\n    width:500px;\n}</style><div class=\"highlight\"><pre class=\"language-css\"><code class=\"language-css\"><span class=\"token selector\">body .my-input-class</span> <span class=\"token punctuation\">{</span>\n    <span class=\"token property\">width</span><span class=\"token punctuation\">:</span>500px<span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span></code></pre></div>"}