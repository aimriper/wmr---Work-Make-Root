Legal Framework & Compliance Guide
To ensure the Collaborative Herd License (CHL) is enforceable and to protect the integrity of the WMR (Work Make Root) project, all contributors and users must adhere to the following technical and administrative roadmap.

1. Technical Integration (Code Shielding)
The license is only effective if it is explicitly linked to the source code.

Master License File: Ensure the LICENSE file (no extension) is present in the root directory of the repository.

File Header (Boilerplate): Include the following comment block at the beginning of all primary source files (e.g., .js, .py, .cpp):

Plaintext
/*
 * WMR - Work Make Root
 * Copyright (c) 2026 Victor Alfonso Nuñez Vallejo
 * Licensed under the Collaborative Herd License (CHL).
 * Refer to the LICENSE file in the root directory for full terms.
 */
NOTICE File: Maintain a NOTICE.txt file listing all original authors of third-party libraries used within this project to ensure international transparency.

2. Active Acceptance (EULA)
To ensure users are aware of their obligations, implement "Active Acceptance":

CLI Prompt: If WMR is executed via CLI, include a mandatory prompt upon wmr install or wmr init:

"This software is governed by the Collaborative Herd License (CHL). By continuing, you agree to its terms and obligations regarding open-source reciprocity. See [LICENSE_URL] for details."

Web/SaaS: Include a link to the license in the application footer and a mandatory "I Accept the CHL Terms" checkbox during account registration or initial configuration.

3. Public Registration (Proof of Authorship)
While copyright is automatic upon creation, formal registration provides significant procedural advantages in international litigation.

SAPI Registration (Venezuela): As the project is based in Caracas, register WMR as a "Software-based Work" with the SAPI (Servicio Autónomo de la Propiedad Intelectual).

Documentation: Prepare the source code, a technical user manual, and a copy of the CHL to submit to the office.

Legal Badge: Once registered, add the following to your README.md:

"Registered software at SAPI under the laws of the Bolivarian Republic of Venezuela [Registration Number]."

4. Vigilance & Enforcement
The strength of a license relies on the author's capacity to enforce it.

Public Repository: Keep the repository Public on GitHub to maximize community-led oversight.

Monitoring: If a fork or derivative work is identified using this code commercially without respecting the "Reciprocity" or "AI Contribution" clauses, issue a formal "Cease and Desist" notice citing the CHL terms.

Community Auditing: Encourage the herd to report non-compliant closed-source implementations. Transparency is our greatest defense.

Why USAGE.md?
Standardization: GitHub users instinctively look for USAGE.md or README.md to understand how to interact with a project.

Clarity: By formalizing this in English, you lower the barrier to entry for international contributors, ensuring the "Herd" can grow globally while remaining legally protected.
