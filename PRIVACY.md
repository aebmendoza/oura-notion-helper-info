# Personal Oura Notion Helper privacy notice

This tool is operated solely by its owner for the owner's own Oura and Notion accounts. It does not accept other users.

The tool requests Oura's `daily` permission. That permission covers daily summaries of sleep, activity, and readiness; the tool retrieves only daily sleep and readiness. It also reads matching entries and the required schema from the owner's Notion recovery ledger to identify existing and missing summaries.

During the current read-only pilot, the tool sends no health records to Notion. If copying is separately approved, it creates summary properties and matching identifiers in Notion, without attaching raw Oura JSON or child blocks. Oura and Notion process data under their own policies.

OAuth credentials and operating state are kept in restricted files on the owner's computer. Raw provider responses are processed in memory; the tool's reports contain dates, counts, and status rather than raw health records or secrets. This public repository contains neither health data nor credentials. The tool has no advertising, data sales, or application analytics.

The owner controls retention of local credentials, operating state, and any Notion entries. Stopping the tool or revoking access does not automatically delete existing Notion entries. The owner can revoke access through the relevant provider and separately remove local credentials or records when desired.

Questions may be directed to the operator using the contact address supplied in the Oura application registration. Do not post health records, tokens, or authorization URLs in public GitHub issues.
