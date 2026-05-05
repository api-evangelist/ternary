---
title: "Ternary enhancements: FinOps roundup February 2026"
url: "https://ternary.app/blog/finops-roundup-february-2026/"
date: "Mon, 09 Mar 2026 16:34:34 +0000"
author: "Ternary Team"
feed_url: "https://ternary.app/blog/feed/"
---
<h2 class="wp-block-heading" id="h-february-finops-roundup-2026">February FinOps roundup 2026</h2>



<p>Welcome to the February 2026 edition of our monthly FinOps feature roundup. Each month, we highlight a selection of the latest Ternary innovations designed to help you drive accountability and maximize technology spend efficiency.</p>



<p>In January, we introduced enhancements to budgets and reports, support for Databricks, and multi-channel Slack notifications. Our February 2026 FinOps roundup highlights Custom Metrics, the new Optimization Hub, Data Layers in reporting, and expanded cost allocation capabilities.</p>



<p>Read on to explore how these updates help teams measure what matters, optimize more effectively, and manage costs with greater precision in Ternary.</p>



<h3 class="wp-block-heading">Custom Metrics</h3>



<p>Custom Metrics give you the flexibility to define your own calculations directly within Ternary, enabling you to transform raw cloud cost data into business-specific metrics without exporting to external tools.</p>



<h3 class="wp-block-heading">Spreadsheet-style formula editor</h3>



<p>Build formulas in a code editor with line numbers and syntax highlighting. Standard arithmetic operators and parentheses are supported for order of operations, making it easy to create metrics such as Effective Savings Rate using formulas like (ListCost &#8211; EffectiveCost) / ListCost.</p>



<h3 class="wp-block-heading">Guided column sidebar</h3>



<p>Available columns are grouped and displayed in a unified sidebar, with FOCUS standard columns highlighted. You can click to insert any column or function directly into your formula, reducing errors and speeding up metric creation.</p>



<h3 class="wp-block-heading">Metric management</h3>



<p>Name and save your metrics, then add them as measures to any report in the Ternary Reporting Engine. Because formulas prioritize FOCUS standard columns, you can write once and measure consistently across cloud providers.</p>



<p>Custom Metrics moves Ternary beyond cost visibility alone. By enabling users to define their own business logic directly on cloud billing data, teams can normalize costs, calculate savings rates, and layer efficiency metrics into their reporting workflows. Custom Metrics is now available in Private Beta — contact your Customer Success Manager or email support@ternary.app to enable it in your environment.</p>



<h2 class="wp-block-heading">Introducing the Optimization Hub</h2>



<p>The Ternary Optimization Hub is a new multi-cloud experience that simplifies how teams surface and act on savings opportunities across AWS, Azure, and Google Cloud.</p>



<p>This centralized dashboard brings together usage, rate, and anomaly insights with interactive filters and KPIs to help you quickly identify high-impact savings across your environment. Ternary already provides resource utilization recommendations by service and provider. With the Optimization Hub, these insights are now unified into two clear categories — idle recommendations and rightsizing recommendations — so you can easily filter, refine, and drill into specific opportunities with greater clarity and control.</p>



<p>The Optimization Hub enables you to prioritize action more effectively, collaborate with better context, and unlock greater value from your multi-cloud spend.</p>



<h2 class="wp-block-heading">More powerful and flexible Ternary Reports</h2>



<p>We’ve introduced several enhancements to the Ternary Reporting Engine that give you more ways to visualize, compare, and filter your data.</p>



<h3 class="wp-block-heading">Data Layers</h3>



<p>You can now add a second dataset to any report and visualize both on a single chart. Data Layers make it easier to compare and correlate metrics — such as cost versus usage, cloud spend versus business KPIs, or cross-cloud comparisons — without leaving the report builder. Previously, this required creating separate reports and comparing across multiple tabs.</p>



<h3 class="wp-block-heading">Advanced boolean filtering</h3>



<p>Report filtering now supports explicit boolean logic. You can control how filters are combined by selecting whether conditions are evaluated using AND or OR logic, enabling more precise queries and more customized views of your data.</p>



<h3 class="wp-block-heading">Budget overlays in reports</h3>



<p>You can now add budgets directly to reports. Budgets appear as overlay lines on charts and as variance columns in tables, giving you an at-a-glance view of how actual cloud spend compares to plan. Budget overlays render seamlessly when reports are pinned to dashboards, ensuring budget tracking is visible alongside your other key metrics.</p>



<h3 class="wp-block-heading">Vendor icons in the report builder</h3>



<p>Each measure and grouping in the report configuration sidebar now displays a vendor icon alongside the field name. This reduces confusion when building multi-vendor reports, since many providers use similar tag names across platforms.</p>



<p>Together, these improvements help teams explore data more efficiently, compare metrics in context, and build reports with greater confidence.</p>



<h2 class="wp-block-heading">Enhanced cost allocation and data management</h2>



<p>We’ve expanded the flexibility and transparency of billing rules, custom labels, and custom data integrations to give teams more control over how costs are distributed and tracked.</p>



<h3 class="wp-block-heading">Expanded dynamic weighting for billing rules</h3>



<p>You can now use any available measure when creating a dynamic weighted billing rule. Previously limited to Billed Cost, Consumed Quantity, and Effective Cost, dynamic weighting now supports all measures in your tenant, allowing teams to distribute costs based on a broader range of metrics.</p>



<h3 class="wp-block-heading">Metric classification for custom data integrations</h3>



<p>Custom measures can now be classified as either Cost or Utilization when configuring data mappings. Previously, all custom metrics defaulted to cost-based measures. This update ensures metrics behave correctly in reports and analytics based on their measurement type.</p>



<h3 class="wp-block-heading">Processing visibility for custom labels and billing rules</h3>



<p>You can now view when processing started, its current state, and when it completed for both custom labels and billing rules. This additional transparency helps confirm when updates have been applied and provides clearer insight into processing timelines.</p>



<h2 class="wp-block-heading">Legacy billing reports to be retired</h2>



<p>With the full transition to FOCUS Billing, all Ternary data and reporting now comes from this modern, unified pipeline. As a result, we are deprecating the legacy billing data source and the reports built on it.</p>



<p><strong>Key dates:</strong> &#8211; <strong>March 2, 2026:</strong> Ternary will stop importing data from the legacy billing pipeline. Reports using “Billing” as the data source will no longer update but will remain visible in your tenant. &#8211; <strong>July 31, 2026:</strong> All legacy billing reports will be permanently removed from the platform.</p>



<p>To continue tracking your cloud spend, we recommend migrating any reports still using the legacy “Billing” source to the new FOCUS Billing data source.</p>



<hr class="wp-block-separator has-alpha-channel-opacity" />



<p>The Ternary team is here to support your FinOps journey. Thanks for reading our February 2026 FinOps roundup. Stay tuned for next month’s updates!</p>



<div class="wp-block-group has-sky-blue-background-color has-background">
<p class="has-text-align-center has-white-color has-text-color has-link-color wp-elements-07cbcc9a0df909127bcdcb0eff832657"><strong>See the Ternary platform in action!</strong></p>



<div class="wp-block-buttons is-content-justification-center is-layout-flex wp-container-core-buttons-is-layout-a89b3969 wp-block-buttons-is-layout-flex">
<div class="wp-block-button"><a class="wp-block-button__link has-black-background-color has-background wp-element-button" href="https://ternary.app/demo/">Request a demo</a></div>
</div>
</div>
<p>The post <a href="https://ternary.app/blog/finops-roundup-february-2026/">Ternary enhancements: FinOps roundup February 2026</a> appeared first on <a href="https://ternary.app">Ternary</a>.</p>
