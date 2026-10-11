<div align="center">

# Hi, I'm Lesedi 👋

<a href="https://www.lvmolemi.com/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&pause=1200&color=8B5CF6&center=true&vCenter=true&width=560&lines=I+build+the+systems+behind+the+screen.;Back-end+engineer+%40+Capitec+Business+Bank;Professional+Lambda+wrangler+%F0%9F%A4%A0;Terraform+apply+and+a+little+prayer+%F0%9F%99%8F" alt="Typing intro" />
</a>

[![Website](https://img.shields.io/badge/lvmolemi.com-8B5CF6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.lvmolemi.com/)
[![Blog](https://img.shields.io/badge/the_blog-1f2937?style=for-the-badge&logo=rss&logoColor=white)](https://www.lvmolemi.com/blog)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lvmolemi/)
[![X](https://img.shields.io/badge/@LVMolemi-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/LVMolemi)

</div>

---

```yaml
lesedi:
  role:       Software Engineer, Back-End
  team:       BB Digital App @ Capitec Business Bank
  promoted:   Oct 2026  # support -> engineer 🎉
  home:       Pretoria  # office: Sandton
  builds:     the systems behind the screen
  stack:      Java ☕ · Spring Boot · AWS · many Lambdas
  weakness:   a beautiful UI 💜
  motto:      bias for action 🏎️
```

## 🧭 The origin story, short version

I started in **support** at Capitec Business Bank in November 2024. That's where I learned the codebase the hard way: fixing escalated client issues, shipping production fixes, helping redesign the front end in React and running releases for the Business Banking app.

In **October 2026** I moved over to **Software Engineer: Back-End** on the BB Digital App product team. I now build new features across the back end *and* the front end of the app. Same codebase, much bigger sandbox. 🏖️

## 🛠️ Things I've built after hours

| | Project | What it does |
|---|---|---|
| 📄 | [**Customer Statements**](https://github.com/Lesmol/customer-statements_springboot) | An API gateway in front of three Spring Boot services. Every request gets checked against Dex (OIDC), files go to S3, and pre-signed URLs are cached in Redis. |
| 🔍 | [**Statement Analysis**](https://github.com/Lesmol/statement-analysis_springboot) | Upload a bank statement and get it read for you. A Spring Modulith on Lambda: Textract pulls the text out of the PDF, Claude writes the insights, SNS/SQS move things along, and Terraform sets it all up across two regions. ([frontend](https://github.com/Lesmol/statement-analysis_react) · [infra](https://github.com/Lesmol/statement-analysis_terraform)) |
| 📈 | [**Market Financials**](https://github.com/Lesmol/market-financials_lambda) | A containerised Python Lambda that serves financial statements. The API keys are checked by a Python authoriser against DynamoDB, [and there's also a Rust version](https://github.com/Lesmol/market-financials-auth-rust_lambda) because why not 🦀 |
| 💌 | [**Email API**](https://github.com/Lesmol/email-api_springboot) | Turns Thymeleaf templates into market update emails and sends them through SES, running as a containerised Lambda. |
| 🛡️ | [**Custos**](https://github.com/Lesmol/custos_springboot) | A guardian for the Solana chain. Latin for "keeper". Currently in the lab. 🧪 |
| ⌨️ | [**market-cli**](https://github.com/Lesmol/market-cli) | Market data from the command line, for people who think browsers are a lot. |

### 🐣 → 🦅 The saga of the market email

It started as one little .NET Lambda that emailed me market data twice a week. It grew up into **four**: a data Lambda, an authoriser, a financials service and a full Spring Boot Email API, with Terraform holding it all together.
I wrote up the whole thing, mistakes included: **[From One Lambda to Four →](https://www.lvmolemi.com/blog/email-api)**

## ✍️ Fresh from the blog

- 📬 [From One Lambda to Four: How My Market Emails Grew Up](https://www.lvmolemi.com/blog/email-api) · *Oct 2026*
- 🧮 [Breakdown: Mapping any excel file into objects](https://www.lvmolemi.com/blog/excel-mapper) · *May 2025*
- ☁️ [Migrating over to Next.js, AWS and more...](https://www.lvmolemi.com/blog/aws-migration) · *Mar 2025*
- 🤖 [I tried an Open Source AI model for Image Recognition](https://www.lvmolemi.com/blog/ai-experiment) · *Aug 2024*

## 🧰 The toolbox

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=java,spring,cs,dotnet,py,rust,aws,terraform,docker,postgres,redis,githubactions,ts,react,nextjs,vite,tailwind,git&perline=9)](https://skillicons.dev)

</div>

<div align="center">

---

<sub>Built with ☕, Terraform and a bit of whimsy · come say hi at <a href="https://www.lvmolemi.com/">lvmolemi.com</a> ✨</sub>

</div>
