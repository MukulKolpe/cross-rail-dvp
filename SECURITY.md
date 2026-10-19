# Security Policy

## Scope

OTAS Cross-Rail DvP is a **research and educational** artifact under the OTAS Lab charter.

- The contracts are **not audited** and are **not intended for production**.
- Everything here targets **test networks only** (Ethereum Sepolia, Sui testnet, or local nodes).
- The live runner generates plain private keys into a local, git-ignored file. **Never** send real assets to these addresses or reuse these keys anywhere else.

## Reporting a vulnerability

Even test-only code can mislead people who copy it, so we still want to hear about flaws — for example, a way to drain or redirect an escrow, bypass an eligibility check, or leak a key from the runner.

Please report privately through **GitHub's private vulnerability reporting**: open the repository's **Security** tab and choose **Report a vulnerability**. Do not open a public issue for a vulnerability.

Include what you found, how to reproduce it, and its impact. A maintainer will acknowledge the report, agree a fix with you, and credit you in the fix unless you prefer otherwise.

## Out of scope

- Behaviour that is documented as a simplification of the demo (for example, demo credentials being hashed JSON rather than signed W3C credentials).
- Issues in third-party code we reference: report problems in [Sui PAS](https://github.com/MystenLabs/pas) or [forge-std](https://github.com/foundry-rs/forge-std) to those projects.
