<img width="7437" height="2376" alt="Helicone GitHub Banner" src="https://github.com/user-attachments/assets/cd3c955b-2ec7-414d-803b-98b2deec2f77" />

<div align="center">
   <h1>Helicone AI</h1>
      <div>
      <img src="https://img.shields.io/badge/License-Apache%20V2.0-red.svg?style=flat-square" alt="Apache V2.0">
      <a href="https://www.ycombinator.com/companies/helicone"><img src="https://img.shields.io/badge/Y%20Combinator-W23-orange?style=flat-square" alt="Y Combinator W23"></a>
      <a href="https://www.npmjs.com/package/@helicone/helicone"><img src="https://img.shields.io/npm/v/@helicone/helicone?style=flat-square&label=npm+@helicone/helicone" alt="helicone npm package"></a>
      <a href="https://www.npmjs.com/package/@helicone/prompts"><img src="https://img.shields.io/npm/v/@helicone/prompts?style=flat-square&label=npm+@helicone/prompts" alt="helicone prompt npm package"> </a>
   </div>
   <h3>
      <a href="https://docs.helicone.ai/getting-started/quick-start">
         <strong>Get started in less than 1 minute</strong>
      </a>
   </h3>
   <div>
   <h4>
      <a href="https://us.helicone.ai/signup">
         Sign up
      </a> · 
      <a href="https://docs.helicone.ai/getting-started/quick-start#explore-features">
         Features
      </a> · 
       <a href="https://helicone.ai/models">
         Models
      </a> · 
      <a href="https://www.helicone.ai/contact">
         Talk to us
      </a>
   </h4>
</div>
</div>

## 🔌 Integrate today
```javascript
import { OpenAI } from "openai";

const client = new OpenAI({
  baseURL: "https://ai-gateway.helicone.ai",
  apiKey: process.env.HELICONE_API_KEY
});

const response = await client.chat.completions.create({
  model: "claude-4.5-haiku", // Or 100+ other models - helicone.ai/models
  messages: [{ role: "user", content: "Hello, world!" }],
});
```

## ⚡️ Why integrate?
<ul style="list-style-type: none;">
   <li>Single line integration (just change the <code>baseUrl</code>)</li>
   <li>Observability by default - trace, monitor, and observe every LLM</li>
   <li>Automatic failover (no more 429s!)</li>
   <li>Always pick the cheapest provider</li>
   <li>Model management, response caching, rate limits, and model routing</li>
   <li>Prompt management, versioning, and playground</li>
   <li>Export to Pothog for custom dashboards</li> 
   <li>Enterprise compliant</li>
</ul>

## Learn more

<div>
   <a href="https://docs.helicone.ai/getting-started/quick-start"><strong>Docs</strong></a> ·
   <a href="https://www.helicone.ai/blog"><strong>Blog</strong></a> · 
   <a href="https://www.helicone.ai/email-signup"><strong>Newsletter</strong></a> · 
   <a href="https://discord.gg/XdmWrRUF"><strong>Discord</strong></a> · 
   <a href="https://docs.helicone.ai/rest/user/post-v1userquery"><strong>API</strong></a> 
</div>
