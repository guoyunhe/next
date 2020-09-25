{"title":"Disable","meta":{"title":"Disable","description":"\n<p>Disable tabs by passing <code>disabled</code> to <code>Tab.Item</code>.</p>\n","order":"8"},"codes":{"jsx":"import { Tab } from '@alifd/next';\n\nReactDOM.render(\n    <Tab>\n        <Tab.Item title=\"Tab 1\" disabled key=\"1\">Tab 1 content</Tab.Item>\n        <Tab.Item title=\"Tab 2\" key=\"2\">Tab 2 content</Tab.Item>\n        <Tab.Item title=\"Tab 3\" key=\"3\">Tab 3 content</Tab.Item>\n    </Tab>\n    , mountNode);\n","css":".next-tabs-content {\n    color: #333;\n    font-size: 12px;\n    padding: 12px;\n}\n"},"body":"\n````jsx\nimport { Tab } from '@alifd/next';\n\nReactDOM.render(\n    <Tab>\n        <Tab.Item title=\"Tab 1\" disabled key=\"1\">Tab 1 content</Tab.Item>\n        <Tab.Item title=\"Tab 2\" key=\"2\">Tab 2 content</Tab.Item>\n        <Tab.Item title=\"Tab 3\" key=\"3\">Tab 3 content</Tab.Item>\n    </Tab>\n    , mountNode);\n````\n\n````css\n.next-tabs-content {\n    color: #333;\n    font-size: 12px;\n    padding: 12px;\n}\n````","html":"<script>(function(){\"use strict\";\n\nvar _next = require(\"@alifd/next\");\n\nReactDOM.render(React.createElement(\n    _next.Tab,\n    null,\n    React.createElement(\n        _next.Tab.Item,\n        { title: \"Tab 1\", disabled: true, key: \"1\" },\n        \"Tab 1 content\"\n    ),\n    React.createElement(\n        _next.Tab.Item,\n        { title: \"Tab 2\", key: \"2\" },\n        \"Tab 2 content\"\n    ),\n    React.createElement(\n        _next.Tab.Item,\n        { title: \"Tab 3\", key: \"3\" },\n        \"Tab 3 content\"\n    )\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Tab <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span>\n    <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>Tab 1<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">disabled</span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>1<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Tab 1 content</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>Tab 2<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>2<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Tab 2 content</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Tab.Item</span></span> <span class=\"token attr-name\">title</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>Tab 3<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">key</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>3<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Tab 3 content</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Tab</span></span><span class=\"token punctuation\">></span></span>\n    <span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div><style type=\"text/css\">.next-tabs-content {\n    color: #333;\n    font-size: 12px;\n    padding: 12px;\n}</style><div class=\"highlight\"><pre class=\"language-css\"><code class=\"language-css\"><span class=\"token selector\">.next-tabs-content</span> <span class=\"token punctuation\">{</span>\n    <span class=\"token property\">color</span><span class=\"token punctuation\">:</span> #333<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">font-size</span><span class=\"token punctuation\">:</span> 12px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">padding</span><span class=\"token punctuation\">:</span> 12px<span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span></code></pre></div>"}