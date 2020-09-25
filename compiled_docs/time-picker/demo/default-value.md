{"title":"默认值","meta":{"title":"默认值","description":"\n<p>可以通过 <code>defaultValue</code> 传入默认时间值，并且可以通过选择改变该值。<code>onChange</code> 回调参数的值的类型取决于 <code>defaultValue</code> 的类型。</p>\n","order":"1"},"codes":{"jsx":"import { TimePicker } from '@alifd/next';\nimport moment from 'moment';\n\nconst defaultVal = moment('12:00:00', 'HH:mm:ss', true);\n\nReactDOM.render(<div>\n    <TimePicker defaultValue={defaultVal} onChange={(val) => console.log(val)} /><br /><br />\n    <TimePicker defaultValue=\"12:00:00\" onChange={(val) => console.log(val)} />\n</div>, mountNode);\n"},"body":"\n\n````jsx\nimport { TimePicker } from '@alifd/next';\nimport moment from 'moment';\n\nconst defaultVal = moment('12:00:00', 'HH:mm:ss', true);\n\nReactDOM.render(<div>\n    <TimePicker defaultValue={defaultVal} onChange={(val) => console.log(val)} /><br /><br />\n    <TimePicker defaultValue=\"12:00:00\" onChange={(val) => console.log(val)} />\n</div>, mountNode);\n````","html":"<script>(function(){'use strict';\n\nvar _next = require('@alifd/next');\n\nvar _moment = require('moment');\n\nvar _moment2 = _interopRequireDefault(_moment);\n\nfunction _interopRequireDefault(obj) { return obj && obj.__esModule ? obj : { default: obj }; }\n\nvar defaultVal = (0, _moment2.default)('12:00:00', 'HH:mm:ss', true);\n\nReactDOM.render(React.createElement(\n    'div',\n    null,\n    React.createElement(_next.TimePicker, { defaultValue: defaultVal, onChange: function onChange(val) {\n            return console.log(val);\n        } }),\n    React.createElement('br', null),\n    React.createElement('br', null),\n    React.createElement(_next.TimePicker, { defaultValue: '12:00:00', onChange: function onChange(val) {\n            return console.log(val);\n        } })\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> TimePicker <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n<span class=\"token keyword\">import</span> moment <span class=\"token keyword\">from</span> <span class=\"token string\">'moment'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> defaultVal <span class=\"token operator\">=</span> <span class=\"token function\">moment</span><span class=\"token punctuation\">(</span><span class=\"token string\">'12:00:00'</span><span class=\"token punctuation\">,</span> <span class=\"token string\">'HH:mm:ss'</span><span class=\"token punctuation\">,</span> <span class=\"token boolean\">true</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">TimePicker</span></span> <span class=\"token attr-name\">defaultValue</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>defaultVal<span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">onChange</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">(</span><span class=\"token parameter\">val</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> console<span class=\"token punctuation\">.</span><span class=\"token function\">log</span><span class=\"token punctuation\">(</span>val<span class=\"token punctuation\">)</span><span class=\"token punctuation\">}</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">TimePicker</span></span> <span class=\"token attr-name\">defaultValue</span><span class=\"token attr-value\"><span class=\"token punctuation attr-equals\">=</span><span class=\"token punctuation\">\"</span>12:00:00<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">onChange</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">(</span><span class=\"token parameter\">val</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> console<span class=\"token punctuation\">.</span><span class=\"token function\">log</span><span class=\"token punctuation\">(</span>val<span class=\"token punctuation\">)</span><span class=\"token punctuation\">}</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}