<p align="center">
  <img src="assets/header.svg" alt="Kamil Szostok — software and AI/ML engineer: .NET / C#, Next.js, T-SQL. ERP integrations, add-ons and LLM automation. Founder of KARQIS and Auspicon." width="100%">
</p>

<p align="center">
  <a href="https://karqis.pl"><img src="https://img.shields.io/badge/karqis.pl-1f3bd3?style=for-the-badge&logoColor=white" alt="karqis.pl"></a>&nbsp;
  <a href="https://auspicon.com"><img src="https://img.shields.io/badge/auspicon.com-0f1115?style=for-the-badge&logoColor=white" alt="auspicon.com"></a>&nbsp;
  <a href="https://github.com/KARQIS-PL"><img src="https://img.shields.io/badge/KARQIS--PL_on_GitHub-24292f?style=for-the-badge&logo=github&logoColor=white" alt="KARQIS-PL on GitHub"></a>
</p>

Software and AI / ML engineer. I build software that sits between business systems: integrations and add-ons for ERP, e-commerce and warehouse platforms, LLM-based automation on top of them, and the products behind two brands I run, **KARQIS** and **Auspicon**. Based in Bielsko-Biała, Poland.

Most of my day-to-day work is commercial and lives in private repositories under [KARQIS-PL](https://github.com/KARQIS-PL). What is public is here.

## What I do

<table>
  <tr>
    <th align="left" width="50%">ERP integrations</th>
    <th align="left" width="50%">ERP add-ons</th>
  </tr>
  <tr valign="top">
    <td>
      Two-way data flows between ERP, online stores, WMS, CRM and accounting: orders, stock levels, prices, documents.<br><br>
      REST APIs, webhooks, file exchange (XML / CSV / XLSX), direct database access when nothing else is available. Idempotent, logged, and safe to re-run.
    </td>
    <td>
      Extensions that live inside the ERP: importers, custom printouts and reports, validation rules, background jobs, UI plug-ins.<br><br>
      Built against vendor SDKs and COM / native APIs, with T-SQL doing the heavy lifting where it belongs.
    </td>
  </tr>
  <tr>
    <th align="left">AI / ML engineering</th>
    <th align="left">Products &amp; SaaS</th>
  </tr>
  <tr valign="top">
    <td>
      LLM features wired into real business processes: document and e-mail extraction, product data enrichment, review replies, classification and agent workflows with tool use.<br><br>
      Evaluation, prompt and context engineering, cost control. Claude, OpenAI and Gemini APIs, MCP servers and skills for coding agents.
    </td>
    <td>
      Off-the-shelf tools sold through the KARQIS store, licensing infrastructure, and Auspicon, a B2B SaaS built on Next.js that monitors how AI assistants talk about a business.<br><br>
      From first prototype through deployment and ongoing maintenance.
    </td>
  </tr>
</table>

## ERP systems I work with

| System | Typical work |
|---|---|
| **InsERT Subiekt nexo PRO** | Sfera / SDK add-ons, importers, reporting, database-level integrations |
| **Comarch ERP Optima** | COM API automation, custom SQL functions and printouts, integrations |
| **Comarch ERP XL** | XL API, Hydra add-ons, T-SQL procedures and triggers |
| **E-commerce &amp; WMS** | Store, marketplace and warehouse connectors: stock sync, order import, price lists |

## Stack

**Core**

<p>
  <a href="#"><img src="https://skillicons.dev/icons?i=cs,dotnet&theme=dark" height="56" alt="C#, .NET"></a>&nbsp;<a href="#"><img src="assets/tsql.svg" height="56" alt="T-SQL / SQL Server"></a>&nbsp;<a href="#"><img src="https://skillicons.dev/icons?i=nextjs&theme=dark" height="56" alt="Next.js"></a>
</p>

**Also in daily use**

<p>
  <img src="https://skillicons.dev/icons?i=ts,react,tailwind,nodejs,py,electron,postgres,docker,githubactions&theme=dark&perline=9" height="48" alt="TypeScript, React, Tailwind CSS, Node.js, Python, Electron, PostgreSQL, Docker, GitHub Actions">
</p>

**AI / ML**

<p>
  <img src="https://img.shields.io/badge/Claude_API-24292f?style=for-the-badge&logo=claude&logoColor=white" alt="Claude API">
  <img src="https://img.shields.io/badge/OpenAI_API-24292f?style=for-the-badge&logoColor=white" alt="OpenAI API">
  <img src="https://img.shields.io/badge/Gemini_API-24292f?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini API">
  <img src="https://img.shields.io/badge/MCP-24292f?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="Model Context Protocol">
  <img src="https://img.shields.io/badge/LangChain-24292f?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/PyTorch-24292f?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Hugging_Face-24292f?style=for-the-badge&logo=huggingface&logoColor=white" alt="Hugging Face">
</p>

## Brands

<table>
  <tr valign="top">
    <td width="50%">
      <a href="https://karqis.pl"><img src="https://avatars.githubusercontent.com/u/319753840?s=96" width="48" align="left" alt="KARQIS" style="margin-right:12px"></a>
      <h3><a href="https://karqis.pl">KARQIS</a> &nbsp;<sub>karqis.pl</sub></h3>
      <p>Software house and product store. Ready-to-buy tools for Polish businesses, such as the product importer for Subiekt nexo PRO, and custom work: ERP add-ons, ERP / WMS / e-commerce integrations and AI-assisted automation. Fixed scope and price agreed before work starts.</p>
    </td>
    <td width="50%">
      <h3><a href="https://auspicon.com">Auspicon</a> &nbsp;<sub>auspicon.com</sub></h3>
      <p>B2B SaaS for AI visibility. Tracks what ChatGPT, Gemini, Perplexity and Claude say about a business, drafts replies to Google reviews, and shows which AI bots crawl the company website. Weekly report, zero setup on the client side.</p>
    </td>
  </tr>
</table>

## Open source

| Repository | What it is |
|---|---|
| [KARQIS-PL/karqis-skill-builder](https://github.com/KARQIS-PL/karqis-skill-builder) | Windows-first workbench for building, auditing and deploying coding-agent skills across Claude Code, Codex, Cursor and Windsurf. Electron + React + TypeScript, MIT. |

## Contact

Integration or ERP add-on in mind? The quickest route is the contact form at [karqis.pl](https://karqis.pl/kontakt). I reply in Polish or English.

<p align="right"><sub>Pixel accent borrowed from the KARQIS logotype.</sub></p>
