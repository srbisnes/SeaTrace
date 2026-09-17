# SeaTrace

**Traceability Infrastructure — by ElCryptoBoy**

SeaTrace is an evidence-first traceability workspace for seafood operations. It connects operational lots, documentary evidence, cryptographic hashes, compliance controls, audit workflows and an Algorand-ready evidence layer.

## Current flow

Register → Lot → Evidence document → SHA-256 → Evidence Vault → Audit → Buyer verification.

## Architecture

- Vite + TypeScript frontend
- AppDeploy backend/API
- Private evidence storage
- SHA-256 integrity records
- Tenant-scoped records and authenticated API routes
- Algorand-ready backend anchoring flow

## Important

A cryptographic hash proves integrity of the recorded bytes; it does not by itself prove that an operational claim is true. Compliance controls in this MVP are operational controls and are not regulatory certification or legal advice.

## Demo

The functional prototype is currently deployed through AppDeploy. The GitHub repository is the source repository for continued hardening and Vercel migration.
