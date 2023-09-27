# Corelight

## Overview

Welcome to the Corelight Dashboards for Chronicle. These dashboards are designed to provide you with valuable insights and visualizations for your Corelight data. Whether you're a security analyst, network administrator, or IT professional, these dashboards can help you monitor and analyze network traffic effectively.

## Block Structure

For more information on the Block structure and customization, refer to [Looker Marketplace Documentation](https://docs.looker.com/data-modeling/marketplace/customize-blocks#marketplace_blocks_that_use_refinements)

## Technical installation

### Pre-requisites

- This block works with Chronicle datasets in Google BigQuery.
- The BigQuery Export feature needs to be enabled for your Chronicle tenant. (Reach out to your Chronicle representative to set this up.)

### Installation steps

1. Install this block from the marketplace
2. Required installation parameters:

- CONNECTION_NAME: name of the database connection for the Chronicle dataset in BigQuery
- CHRONICLE_URL: this block contains links back to the UDM search in Chronicle. Enter the base URL of your Chronicle tenant, for e.g. https://{your_tenant}.backstory.chronicle.security

3. Access the block from Browse - Applications & Tools - Corelight Block or the LookML dashboards folder (/folders/lookml). You can customize these dashboards by copying them into one of your instance's folders.

### Reference

- For guidance on fully utilizing and analyzing dashboards in Looker, refer to [Looker Guide Documentation](https://cloud.google.com/looker/docs/viewing-dashboards)

### Troubleshooting or Suggestions

We value your feedback and want to ensure that our platform operates seamlessly for you. If you encounter any issues or have suggestions for improvement, please reach out to our support team at <support@example.com>. Please be as detailed as possible in your explanation and we'll address it as quick as we can. Your insights help us enhance our service and provide you with the best experience possible.
