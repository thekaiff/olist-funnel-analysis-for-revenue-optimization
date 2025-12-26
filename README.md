<div align="center">
  <img width="320px" src="Images/logo.png" />
</div>

<h1 align="center">Olist Sales Funnel & Conversion Performance Analysis</h1>

<h3 align="center">Industry: E-Commerce | Online Marketplace</h3>

---

<table align="center">
  <tr>
    <td width="1440">
<h2 align="center">Client Background</h2>

<p>
Olist is a large Brazilian e-commerce marketplace that connects sellers, buyers, and logistics partners through a unified platform. The business operates across multiple product categories and relies heavily on digital marketing channels to acquire sellers and close deals.
</p>

<p>
At the time of analysis, Olist was experiencing <strong>low funnel conversion efficiency</strong> and <strong>limited visibility into post-conversion performance</strong>, making it difficult to understand where leads drop, which channels perform best, and where operational delays occur after deal closure.
</p>

<p>
Reporting to the <strong>Marketing, Sales, and Operations teams</strong>, an end-to-end funnel and operational analysis was conducted using <strong>Python for analysis and Power BI for executive reporting</strong>. The goal was to move the organization from reactive reporting to a <strong>data-driven decision-making framework</strong>.
</p>

<strong>Key Focus Areas of the Analysis:</strong>
<ul>
  <li>Quantifying lead-to-deal conversion performance across the funnel.</li>
  <li>Evaluating marketing channel efficiency and deal velocity.</li>
  <li>Identifying operational bottlenecks in order fulfillment.</li>
</ul>

<p>
The insights from this project support <strong>strategic planning, marketing optimization, and operational improvement initiatives</strong> aimed at improving conversion efficiency and customer experience.
</p>

   </td>
  </tr>
</table>

---

<h2 align="center">Executive Summary</h2>
<table align="center">
  <tr>
    <td width="1440">
      <p>
This project analyzes Olist’s end-to-end sales funnel — from Marketing Qualified Leads (MQLs) to closed deals and order fulfillment — to identify conversion inefficiencies and operational bottlenecks.
      </p>

<strong>High-Level Business Impact:</strong>
<ul>
  <li>Identified an overall <strong>~10.4% MQL → Closed Deal conversion rate</strong>, highlighting significant early-funnel drop-off.</li>
  <li>Revealed <strong>paid and organic search channels</strong> as the most efficient sources, converting up to <strong>~12–15 deals per 100 MQLs</strong>.</li>
  <li>Found that <strong>most deals close within 30 days</strong>, with conversion probability dropping sharply beyond this window.</li>
  <li>Uncovered that <strong>~8% of delivered orders miss estimated delivery timelines</strong>, with the highest variability occurring in the carrier-to-delivery stage.</li>
</ul>

<p>
<strong>Outcome:</strong> A two-page Power BI dashboard enabling leadership to monitor funnel health, channel efficiency, sales performance, and fulfillment reliability through a single, business-segment-driven view.
</p>

   </td>
  </tr>
</table>

---

<h2 align="center">Dashboard Walkthrough</h2>

<table align="center">
  <tr>
    <td align="center">
      <img src="/Images/dashboard_1.gif" style="max-width:100%; height:auto; border-radius:10px;" />
      <p><strong>Executive Performance Overview</strong></p>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="/Images/Dashboard2.jpg" style="max-width:100%; height:auto; border-radius:10px;" />
      <p><strong>Sales & Delivery Insights</strong></p>
    </td>
  </tr>
</table>

---

<h2 align="center">Business Problem</h2>
<table align="center">
  <tr>
    <td width="1440">
<p>
Olist lacked a unified view of how leads progress through the funnel and how operational performance impacts downstream outcomes.
</p>

<ul>
  <li>Which marketing channels generate high-quality leads?</li>
  <li>How fast do deals convert, and where does velocity decline?</li>
  <li>Which fulfillment stages introduce the most delivery risk?</li>
</ul>

<p>
Without this visibility, marketing spend optimization, sales prioritization, and logistics improvements were largely reactive rather than data-driven.
</p>

<strong>Objective:</strong>
Build a structured analytical framework to diagnose funnel drop-offs, quantify conversion efficiency, and identify operational bottlenecks impacting customer experience.
    </td>
  </tr>
</table>

---

<h2 align="center">Methodology & Analytical Approach</h2>
<table align="center">
  <tr>
    <td width="1440">
<ul>
  <li><strong>Exploratory Data Analysis (EDA):</strong> Assessed missing values, distributions, and data consistency across marketing, sales, product, and order datasets.</li>
  <li><strong>Funnel Analysis:</strong> Measured MQL → Closed Deal conversion rates and evaluated performance across channels, lead types, and behavioral profiles.</li>
  <li><strong>Time-Based Analysis:</strong> Analyzed deal closing velocity and order delivery timelines to identify speed-related friction.</li>
  <li><strong>Operational Diagnostics:</strong> Used distribution and variability analysis to isolate fulfillment bottlenecks.</li>
</ul>

<p>
This combination of descriptive and diagnostic analysis enabled a holistic view of both revenue generation and operational execution.
</p>
    </td>
  </tr>
</table>

---

<h2 align="center">Skills & Tools Used</h2>
<table align="center">
  <tr>
    <td width="1440">
<ul>
  <li><strong>Python:</strong> Pandas, NumPy, Matplotlib, Seaborn</li>
  <li><strong>Data Analysis:</strong> Funnel Analysis, Time-to-Event Analysis, Distribution Analysis</li>
  <li><strong>Visualization:</strong> Power BI, DAX, Interactive Slicers</li>
  <li><strong>Business Analytics:</strong> Conversion Metrics, Operational KPIs</li>
</ul>
    </td>
  </tr>
</table>

---

<h2 align="center">Insights Deep-Dive</h2>
<table align="center">
  <tr>
    <td width="1440">

<h3>1. Funnel Conversion Efficiency</h3>
<ul>
  <li>Only <strong>~10.4% of MQLs</strong> convert into closed deals, indicating that nearly <strong>9 out of 10 leads drop</strong> before deal closure.</li>
  <li>Conversion performance varies significantly by acquisition channel, confirming uneven lead quality.</li>
</ul>

<h3>2. Marketing Channel Effectiveness</h3>
<ul>
  <li><strong>Paid Search and Organic Search</strong> deliver the highest efficiency, converting approximately <strong>12–15 closed deals per 100 MQLs</strong>.</li>
  <li>Channels such as <strong>email, display, and social</strong> generate volume but underperform in conversion efficiency, suggesting lead quality issues.</li>
</ul>

<h3>3. Conversion Velocity</h3>
<ul>
  <li>The majority of closed deals occur within <strong>0–30 days</strong> of first contact.</li>
  <li>Deals exceeding <strong>60 days</strong> show a sharp decline in conversion likelihood, signaling diminishing returns on prolonged sales cycles.</li>
</ul>

<h3>4. Operational Fulfillment Bottlenecks</h3>
<ul>
  <li>Average delivery time is approximately <strong>12 days</strong>, but variability is high.</li>
  <li>The <strong>carrier-to-customer delivery stage</strong> exhibits the widest spread and most outliers, identifying it as the primary logistics bottleneck.</li>
  <li>Approximately <strong>8% of delivered orders</strong> arrive later than estimated, directly impacting customer experience.</li>
</ul>

   </td>
  </tr>
</table>

---

<h2 align="center">Results & Business Recommendations</h2>
<table align="center">
  <tr>
    <td width="1440">

<h3>📌 Marketing & Sales Optimization</h3>
<ul>
  <li>Reallocate marketing budget toward <strong>paid and organic search</strong>, which convert up to <strong>2–3× more efficiently</strong> than lower-performing channels.</li>
  <li>Prioritize leads expected to close within <strong>30 days</strong> to maximize sales productivity.</li>
</ul>

<h3>📌 Operations & Fulfillment</h3>
<ul>
  <li>Focus process improvements on the <strong>carrier-to-delivery stage</strong> to reduce variability and missed delivery estimates.</li>
  <li>Use delivery delay metrics as an early-warning KPI to prevent customer dissatisfaction.</li>
</ul>

   </td>
  </tr>
</table>

---

<h2 align="center">Key Learnings</h2>
<table align="center">
  <tr>
    <td width="1440">
<ul>
  <li>Funnel metrics must be modeled carefully to avoid misleading conclusions when datasets operate at different granularities.</li>
  <li>Average values alone hide operational risk — variability analysis is critical for bottleneck identification.</li>
  <li>Strong dashboards focus on decision-making, not just visualization.</li>
</ul>
    </td>
  </tr>
</table>

---

<h2 align="center">Limitations</h2>
<table align="center">
  <tr>
    <td width="1440">
<ul>
  <li>No direct linkage between closed deals and individual orders limited full end-to-end attribution.</li>
  <li>Customer-level retention analysis was constrained by the absence of repeat purchase behavior in the dataset.</li>
</ul>
    </td>
  </tr>
</table>

---

<h2 align="center">Next Steps</h2>
<table align="center">
  <tr>
    <td width="1440">
<ul>
  <li>Integrate deal-to-order identifiers to enable full funnel attribution.</li>
  <li>Extend analysis with cohort-based retention metrics once repeat purchase data is available.</li>
  <li>Deploy dashboard refresh automation for near real-time monitoring.</li>
</ul>
    </td>
  </tr>
</table>


---

<h2 align="center">Contact</h2>
<table align="center">
  <tr>
    <td align="center" width="1440">
      <p>
        If you’d like to discuss the <strong>code</strong>, the <strong>dashboard</strong>, or the <strong>business insights</strong>,
        feel free to reach out via GitHub or email.
      </p>

  <p>
        📧 <strong>Email:</strong> kaifsdkpro@gmail.com
      </p>

  <p>
        📬 <strong>LinkedIn:</strong>
        <a href="https://www.linkedin.com/in/kaifsayed57/" target="_blank">
          linkedin.com/in/kaifsayed57
        </a>
      </p>

  <p>
        ⭐ <strong>If you found this project insightful, don’t forget to star this repository!</strong>
      </p>

  <p>
        Open to Data Analyst, Business Analyst, and Excel / SQL / Power BI–based analytics roles.
      </p>
  <p>
        <em></em>
      </p>
    </td>
  </tr>
</table>

<h4 align="center"><em>Made with ❤️ — Kaif Anis Sayed</em></h4>
