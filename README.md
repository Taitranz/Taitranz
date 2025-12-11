<!-- markdownlint-disable MD033 -->


<h2>
    Hi 👋
</h2>

---

<h3> CompSci & CompSim </h3>

---

<h3> 👨‍🍳 Past Projects: </h3>

<h4> Hooper Music Studio Website </h4>

* Link to website: <a href="https://hoopermusicstudio.com/">HMS</a>

<h4> Seek Music</h4>

* Link to website: <a href="https://seekmusic.pythonanywhere.com/">Seek Music </a>
* Link to post project analysis: <a href="https://blog.taitranz.com/posts/seek-music-post-mortem/">BLOG POST</a>

<h4> Socslingo, and Duolingo clone in Java and JavaFX</h4>

* Link to preview: <a href="https://taitranz.com/">Socslingo</a>
* Link to post project analysis: <a href="https://blog.taitranz.com/posts/socslingo-a-duolingo-inspired-java-clone/">BLOG POST</a>


    
<h4> 📖 Current: </h4>

Valgo is a GPU-accelerated financial charting and trading-analysis desktop application built in Python, designed as the data and tooling layer for a multi-stage AI / algorithmic trading system focused on forex (primarily EUR/USD). It uses a modular, event-driven architecture to handle real-time market data streaming, multi-timeframe candle aggregation, technical pattern detection, and high-performance chart rendering.

The current codebase is centred on data infrastructure and trader tooling: real-time ingestion from brokers, interactive charting, rich market data visualisation, and comprehensive data persistence for research and backtesting. Traders and model developers can manually identify and label high-quality trade setups directly in the UI, generating supervised learning datasets for downstream models.

On top of this, Valgo is designed to support a two-stage model pipeline: a “good-trade” classifier trained on manually labelled profitable trades, and an independent “bad-trade” filter trained to recognise common losing patterns. The intent is for the good-trade model to scan live data for candidate trades, with the bad-trade model acting as a risk and quality gate to reduce false positives before execution. Candidate trades are executed in a paper-trading / simulated environment, with outcomes persisted as structured, model-ready data to support continuous retraining and performance monitoring.

Valgo is now being extended into an agentic trading application. The system is designed to expose structured candle data and broker news feeds to LLMs (e.g. GPT-5.1, Claude Sonnet 4.5, Gemini 3 Grok 4), which run autonomous analysis loops over EUR/USD to produce observations on trend, regime shifts, and risk conditions. These LLM agents sit alongside the quantitative models as an additional reasoning layer, turning raw market and news streams into interpretable, traceable signals that can drive alerts, decision support, and eventually execution logic under strict risk constraints.

The long-term goal is to move from human-in-the-loop decision support to fully agentic trading workflows, where validated models and LLM agents are promoted from research into production, with automated execution and ongoing learning from live trading results.

Recent blog update: https://blog.taitranz.com/posts/valgo-a-frontier-agentic-trading-system-for-eurusd/

* Link to preview: <a href="https://taitranz.com/">Valgo</a>
* Link to blog updates relating to Valgo: <a href="https://blog.taitranz.com/posts/valgo-a-frontier-agentic-trading-system-for-eurusd/">BLOG UPDATES</a>

* Open to software roles — ready to embrace new challenges and relocate for the right opportunity, https://taitranz.com/

<!--
**Taitranz/Taitranz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
