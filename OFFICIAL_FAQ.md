1. Does DVAS store sensitive Voter ID or Social Security data?

No. DVAS operates on a Zero-Storage Mandate. By utilizing Zero-Knowledge Proofs (ZKP), the system allows a user to prove their eligibility on their local device. The server only receives a mathematical "proof" (a cryptographic 'Yes'). We do not create a "Honey Pot" of personal data, significantly reducing the state's liability under Oregon privacy laws.

2. How does this integrate with ORESTAR and existing reporting?

DVAS is designed as a Pre-Verification Utility, not a replacement for ORESTAR. It provides candidates with a "Verified Donor" stream. By the time a report is filed in ORESTAR, the data has already been cryptographically screened for eligibility, reducing the manual audit workload for Elections Division staff.

3. Is this a "Black Box" system? How can it be audited?

Absolutely not. DVAS is Open-Source and Externally Verifiable.

Independent Audit: Any third-party cybersecurity firm can inspect the ZKP logic.

Public Ledger: While donor identities are private, the proofs are public. Anyone can run a simple script to verify that the total number of "Verified Proofs" matches the reported donor count.

4. What happens if the system fails or is offline?

DVAS is a Parallel Transparency Layer. Because it is not integrated into the air-gapped vote-counting machines, a system failure would have zero impact on the casting or counting of ballots. It serves as an enhancement to trust, not a critical point of failure for the election itself.

5. How does DVAS handle the "Postmark Rule" and late data?

DVAS logic follows the ORS 254.485 standards. It timestamps cryptographic proofs in real-time. For the 2026 pilot, it will provide a secondary timestamp that assists auditors in reconciling late-arriving campaign contributions with their verification status.

6. Does DVAS conflict with Citizens United?
No. In fact, DVAS fulfills the "missing promise" of the Citizens United decision. 

Justice Kennedy's majority opinion assumed that "prompt disclosure" would allow voters to see who was paying for ads. However, this led to "Dark Money" because groups feared harassment if they disclosed names. 

DVAS solves this using Zero-Knowledge Proofs (ZKP):
* **For Donors:** It protects First Amendment privacy. You can prove you are an "Eligible Individual" or a "Registered Oregon Voter" without revealing your name or home address to the public.
* **For Auditors:** It provides 100% certainty. While the public doesn't see a name, the DVAS ledger shows a mathematical "Proof of Eligibility." This ensures that 100% of the funds came from legal, verified sources.

7. How does DVAS stop Foreign Interference?
Foreign entities often use shell LLCs to funnel money into U.S. elections—a major loophole in the post-Citizens United era. 

DVAS acts as a "Digital Firewall":
* Every contribution must be accompanied by a DVAS "Citizenship Proof."
* This proof is generated locally on the user's device (using encrypted ID data) and sent to the ledger.
* If a contribution lacks this cryptographic proof, the system flags it immediately as "High Risk for Foreign Influence."
* This allows auditors to spot and block foreign money *before* it is spent, rather than months after the election is over.
