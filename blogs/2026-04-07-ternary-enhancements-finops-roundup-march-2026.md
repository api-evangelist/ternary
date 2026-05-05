---
title: "Ternary enhancements: FinOps roundup March 2026"
url: "https://ternary.app/blog/finops-roundup-march-2026-2/"
date: "Tue, 07 Apr 2026 20:32:22 +0000"
author: "Kyle Rattet"
feed_url: "https://ternary.app/blog/feed/"
---
<h2 class="wp-block-heading" id="h-march-finops-roundup-2026">March FinOps roundup 2026</h2>



<p>March brought focused improvements to reporting, labeling, and workflow flexibility inside Ternary. This month’s releases help teams analyze cloud cost data more clearly, align costs to business context with greater precision, and stay informed where work already happens.</p>



<p>Here’s what we shipped in March.</p>



<h3 class="wp-block-heading"><strong>Visibility Controls</strong></h3>



<p><strong>Report and Dashboard Visibility Controls</strong><strong><br /></strong>New visibility settings allow teams to control who can see specific reports and dashboards. This makes it easier to share insights securely across teams while ensuring appropriate access.</p>



<figure class="wp-block-image size-large"><img alt="" class="wp-image-5569" height="841" src="https://ternary.app/resources/report_visibility-1024x841.webp" width="1024" /></figure>



<h3 class="wp-block-heading"><strong>Reporting Enhancements</strong></h3>



<p><strong>Dual Y‑Axis Support for Data Layers</strong><strong><br /></strong>We added support for dual Y‑axes when working with data layers in charts. This makes it easier to compare metrics that live on very different scales, such as cost and utilization, within the same visualization.</p>



<figure class="wp-block-image size-large"><img alt="" class="wp-image-5570" height="477" src="https://ternary.app/resources/dual_y_axis-1024x477.webp" width="1024" /></figure>



<p><strong>Horizontal Bar Chart Type</strong><strong><br /></strong>A new horizontal bar chart type is now available in reports. This visualization option can help teams better communicate differences in cost or usage across services, accounts, or custom groups.</p>



<figure class="wp-block-image size-large"><img alt="" class="wp-image-5571" height="592" src="https://ternary.app/resources/horizontal_bar_chart-1024x592.webp" width="1024" /></figure>



<p><strong>Improved Table Views for Data Layers</strong><strong><br /></strong>Data layer selection in table views gives you the option to focus on a single dataset when analyzing reports. This enhancement simplifies side‑by‑side analysis when your report contains multiple layers.</p>



<p><strong>Editable Data Layer Names<br /></strong>You can now customize the names of data layers and have those names persist across sessions. This makes reports more readable and easier to share with others.</p>



<p><strong>Budget Overlays in Reports<br /></strong>Budget overlays can now be added directly as a data layer in your reports. This provides clear visibility into planned spend versus actuals, all within your chart views.</p>



<figure class="wp-block-image size-large"><img alt="" class="wp-image-5572" height="508" src="https://ternary.app/resources/budget_overlays-1024x508.webp" width="1024" /></figure>



<h3 class="wp-block-heading" id="h-smarter-cost-context"><strong>Smarter Cost Context</strong></h3>



<p id="h-"><strong>Time Range Support for Custom Labels<br /></strong>All custom label types now support start and end dates. With time range controls, you can define when labels are active, aligning cost allocation to specific initiatives, time‑boxed efforts, or organizational events.</p>



<figure class="wp-block-image size-large"><img alt="" class="wp-image-5573" height="245" src="https://ternary.app/resources/time_based_custom_labels-1024x245.webp" width="1024" /></figure>



<p id="h-"><strong>AI‑Powered Custom Label Recommendations<br /></strong>We introduced AI‑powered suggestions to help you generate meaningful labels automatically. This feature reduces manual work and improves consistency when mapping cloud spend to business context.</p>



<figure class="wp-block-image size-large"><img alt="" class="wp-image-5574" height="563" src="https://ternary.app/resources/AI_powered_custom_label_suggestions-1024x563.webp" width="1024" /></figure>



<h3 class="wp-block-heading" id="h-collaboration-amp-alerts"><strong>Collaboration &amp; Alerts</strong></h3>



<p id="h-"><strong>Slack Notifications for Budgets and Reports<br /></strong>Budget and report notifications can now be delivered via Slack in addition to email. This gives teams more flexibility in how they receive alerts and helps bring cloud cost insights into the flow of everyday collaboration.</p>



<figure class="wp-block-image size-full"><img alt="" class="wp-image-5575" height="990" src="https://ternary.app/resources/reports_slack_channel.webp" width="910" /></figure>



<h3 class="wp-block-heading" id="h-productivity-amp-workflow-improvements"><strong>Productivity &amp; Workflow Improvements</strong></h3>



<p><strong>Clone Custom Measures</strong><strong><br /></strong>Creating a new metric based on an existing one is now faster and easier. You can clone custom measures to use as the starting point for variations without affecting reports that rely on the original.</p>



<p><strong>Reserved Names for Custom Measures</strong><strong><br /></strong>To prevent conflicts with existing vendor or system‑provided values, custom measures can no longer use names that match reserved values. This protects your metrics from accidental overwrites.</p>



<p id="h-"><strong>Optimization Hub Recommendation Count Badge<br /></strong>A new visual badge shows the total number of recommendations available for each optimization type. This gives a quick sense of where the most opportunities live without needing to drill into each category.</p>



<p id="h-"><strong>Enhanced Resource Utilization Export Context<br /></strong>Resource Utilization Insights exports now include richer context such as sub‑account, region, family, and type information at the instance level. These additional columns make it easier to analyze exported data outside of Ternary.</p>



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
<p>The post <a href="https://ternary.app/blog/finops-roundup-march-2026-2/">Ternary enhancements: FinOps roundup March 2026</a> appeared first on <a href="https://ternary.app">Ternary</a>.</p>
