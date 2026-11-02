# Narrative Tool

An AI-assisted clinical documentation tool for behavioral health providers. It turns a clinician's source documents into clear, well-structured narratives, then helps with the paperwork that follows.

## What it does
- Generates structured clinical narratives from uploaded documents, streaming each section in as it's written
- Fills authorization request forms from the finished narrative
- Reads a payer's denial letter and drafts an organized appeal, matching each stated reason to the supporting evidence in the record
- Keeps the clinician in control: ratings and findings are used exactly as the provider documented them, never re-scored by the AI

## Built with
Node.js · React · TypeScript · Amazon Bedrock · AWS (ECS, CloudFront, KMS, CloudTrail, CDK) · Microsoft SSO · GitHub Actions with OIDC (no stored cloud keys)

## How it ships
Every change deploys automatically to a beta environment with zero downtime and automatic rollback; promotion to live is a deliberate manual step.

## Status
In development. The source code is private — reach out if you're interested in the project.
