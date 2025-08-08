---
title: Submit a list of jobs to be indexed
excerpt: >
  Accepts a JSON array of job objects, each with job_id and job_description
  fields, and indexes them. If job_id already exists, it will be updated. If
  replace is true, all existing jobs will be replaced with the provided list. If
  replace is false or omitted, jobs are upserted (added or updated only).
api:
  file: psearch-agent API Docs.yaml
  operationId: post_v1-upsert-jobs
hidden: false
---