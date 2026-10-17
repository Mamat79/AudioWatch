# AudioWatch 0.1.20 — Windows bêta / Windows beta

Version Windows de test avec le bouton « Quitter AudioWatch » : fermeture de l’interface et de l’agent, arrêt de la surveillance, sans modification du routage RME.

Windows test version with a Quit AudioWatch button: closes the desktop and agent and stops monitoring without changing RME routing.

- Windows x64, version applicative / application version: **0.1.20**.
- Provenance Windows privée / private Windows source: `a8dfaea2f9c4e45c6db2d3319238e707605a52e0`.
- Installer: `AudioWatch-0.1.20-Setup.exe` (53,806,235 bytes).
- SHA-256: `cebb8fa9dccf8add19a8e19353ccab7ea2e6a3f73f22cf5f6f0475b81cb8baa0`.

## Vérifications Windows / Windows checks

Deux installations d’essai isolées avaient vérifié le contenu et la conservation des données synthétiques. Le 18 octobre 2026, lancement natif FR avec profil synthétique sûr, puis remplacement personnel standard 0.1.19 → 0.1.20 au même emplacement et avec le même AppId : code de sortie 0, 486 fichiers livrés exacts, 51 fichiers personnels inchangés avant et après lancement/fermeture. Les trois copies de sauvegarde/restauration ont été vérifiées (2 451 fichiers par copie). Le bouton Quitter ferme effectivement Desktop et Agent, sans relance constatée au contrôle différé, sur le profil synthétique et le profil personnel. Surveillance suspendue et démarrage automatique désactivé sur le profil personnel.

Two earlier isolated installer checks verified payload and synthetic-data preservation. On 18 October 2026: safe synthetic FR native launch, then standard personal in-place upgrade 0.1.19 → 0.1.20 with the same AppId and location, exit 0, 486 exact payload files, and 51 personal files unchanged before and after native launch/quit. Three backup/restore copies were verified (2,451 files each). Quit closed Desktop and Agent without observed restart on the delayed check in both profiles. Personal monitoring remained suspended and automatic startup disabled.

## Limites / Limits

Les 112 tests historiques annoncés par le propriétaire des sources ne sont pas de nouveaux tests rejoués ici. Aucune validation matérielle RME/TotalMix, du passage audio, de reprise après incident réel, de surveillance d’un hôte réel ou de matrice complète DPI/langues. L’avertissement sur un ancien secours reste conservé : vérifier manuellement le routage avant exploitation. Installeur non signé.

The source owner's 112 historical tests were not rerun here. Physical RME/TotalMix routing, audio continuity, real incident recovery, real-host monitoring, and full DPI/language coverage remain unverified. The prior-backup warning is preserved; manually check routing before real operation. Unsigned installer.

Publication bêta Windows séparée : les fichiers macOS, les anciennes versions et le brouillon mixte v0.1.20 sont conservés. Cette publication ne modifie pas Latest et ne contient ni sources privées, ni profils personnels, ni journaux locaux.

Separate Windows beta: existing macOS assets, older versions, and the mixed v0.1.20 draft are preserved. This release does not change Latest and includes no private source, personal profile, or local log.
