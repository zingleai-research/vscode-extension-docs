# Zingle AI — **Generate the Business Meaning of Tables & Columns**

> Unlock the untapped knowledge in your **codebase** about your **tables and columns**, so AI agents can truly understand your data schema.

**Zingle AI** is an open-source VS Code extension (by Zingle AI Lab) that scans your application’s **source code** (migrations, ORM models, services, etc.) to automatically generate **rich, business-ready documentation** for your database tables and columns.  
Use it to bridge the gap between raw schema definitions and real business context—so text-to-SQL tools and data AI assistants (Snowflake, Databricks, BigQuery, dbt, etc.) produce **accurate, trustworthy answers**.

<p align="center">
  <a href="https://youtu.be/Erc_7Wk3uHs" target="_blank" rel="noopener noreferrer">
    <img src="https://raw.githubusercontent.com/gitkraken/vscode-gitlens/main/images/docs/get-started-video.png" alt="Watch the Zingle AI overview video" width="520">
  </a>
</p>


## Why this matters

Schemas rarely capture **real business meaning**. That’s why AI answers are often ambiguous.

**Example**

- **Column:** `fare`  
- **Typical doc:** “The fare amount.”  
- **Result:** Confusion (Does it include surge? Tips? Tolls? What about cancelled rides?)

**With Zingle AI**

- **Column:** `fare`  
- **Generated doc:**  
  *“Final computed fare after ride completion. Calculated by the fare engine using distance, duration, base fare, surge multipliers, and tolls. Excludes tips and cancellation fees (captured separately). Null if ride not completed or fare calculation failed.”*  
- **Result:** Clear logic → **trustworthy AI answers**

▶ **Watch “Why Context Matters” (2 min):** https://youtu.be/B64ywqOwdhI

---

## What Zingle AI does

Automatically generates detailed docs for every table and column, including:

- **Business process context** — why it exists, what it represents, how it’s used  
- **Value definitions** — explain codes and enums in business terms (e.g., `C`, `R`, `D`)  
- **Process mapping** — where app logic inserts/updates values; calculations and conditions

This richer context makes assistants like **Snowflake Cortex**, **Databricks Genie**, **dbt Semantic Layer**, **BigQuery AI** more **accurate, reliable, and auditable**.

---

## Examples

See real samples of Zingle-generated docs:  
**🔗 https://zingleai.notion.site/zingle-ai-context-examples**

---

## Requirements

- **VS Code** with an internet connection  
- **Node.js ≥ 18** installed  
- **Windows users:** enable **WSL**

---

## Privacy & Security

- **Your code stays local** — source and generated docs remain on your machine  
- **No external training** — your code is **never** used to train models  
- **Local processing** — documentation generation runs locally

---

## Support

- **Slack:** Join the community — https://join.slack.com/t/zingleai/shared_invite/zt-3c3rp1vpg-6BXpK2eTdwUNogugSDcM~Q  
- **WhatsApp:** Instant help — https://wa.me/919131266517?text=VS-Code%20Extension  
- **Live Demo:** Book a 30-min call — https://calendly.com/founder-zingle/30min  
- **Email:** support@getzingle.com  
- **Website:** https://getzingle.com/  
- **LinkedIn:** https://www.linkedin.com/company/zingleapp/

If Zingle AI helps you, please ⭐ **leave a review**:  
https://marketplace.visualstudio.com/items?itemName=ZingleAI.zingleai-codebase2docs&ssr=false#review-details

---

## License

**MIT**