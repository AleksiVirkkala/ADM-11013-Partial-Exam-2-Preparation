# T09 — Trade Finance: Letter of Credit and Factoring

**Spanish label:** Facturación y pago — Carta de crédito
**Appears in lectures:** L19, L22
**Textbook:** Hill Ch. 16; letter of credit explained **p. 474**
**Exam priority:** HIGH — multiple explicit exam flags; Control Question 4 (L22) is exactly about how parties protect themselves without trust.

## 1. TL;DR
When a buyer and seller in different countries have no basis to trust each other, neither wants to ship first nor pay first. A **Letter of Credit (LC)** inserts two banks between them: the buyer's **issuing bank** promises payment to the seller against **compliant documents**, and the seller's **advising bank** authenticates the LC and handles documents. Counterparty risk is replaced by bank risk (which is cheap — banks charge a fee for it). The linchpin is the Bill of Lading: the buyer can only claim the goods once the issuing bank releases it, and that release happens only after payment/credit is arranged. **Factoring** is a separate, simpler tool: selling receivables to a third party (the "factor") at a discount for immediate cash — a working-capital fix, not a trust substitute.

## 2. Letter of Credit

### 2.1 When and why
- Use case: buyer and seller in different countries, no established trust (e.g., Mexican exporter selling to a buyer in Romania).
- Problem: seller won't ship without a payment guarantee; buyer won't pay without proof of shipment.
- Solution: **shift counterparty risk to banks**. A bank (for a fee) guarantees payment against documents. Bilateral trust → bank-backed promise.
- Common in trade with Asia, Africa, Eastern Europe, Australia; very common in Europe. Rare purely domestically.

### 2.2 Parties (4)
| Party | Role |
|---|---|
| **Buyer** | *Applicant* / importer; asks the issuing bank to open the LC; ultimately obligated to pay. |
| **Seller** | *Beneficiary* / exporter; entitled to be paid on presentation of compliant documents. |
| **Issuing bank** | Buyer's bank. Issues the LC, runs compliance checks on the buyer, is legally obligated to pay the seller against compliant docs. |
| **Advising bank** | Seller's bank (sometimes called *notifying bank*). Authenticates the LC, forwards documents. No payment obligation of its own (unless it also *confirms* the LC). |

If the two banks have no correspondent relationship, a global bank (Citibank, Deutsche Bank, etc.) is often slotted in as correspondent.

### 2.3 Mechanics — Stage 1 (Setup / Opening the LC)
1. **Sale contract signed** between buyer and seller; specifies payment via LC.
2. **Buyer applies** to the issuing bank for the LC. Issuing bank runs compliance/solvency checks on the buyer (effectively extending credit) and sets terms/conditions.
3. **Issuing bank issues the LC** and sends it to the advising bank.
4. **Advising bank forwards** the LC to the seller (after its own authentication checks).
5. **Seller reviews** the LC's terms and conditions carefully. If any condition can't be met, request amendments *now* through the issuing bank — discrepancies later risk losing the payment guarantee.

### 2.4 Mechanics — Stage 2 (Execution / Using the LC)
6. **Seller ships the goods.**
7. **Seller presents documents** required by the LC (the 5 standard trade docs — see [T07](T07%20-%20Export%20Documents%20and%20Flow.md) — plus any extras specified in the LC) to the advising bank, which checks compliance.
8. **Advising bank forwards documents** to the issuing bank, which re-checks compliance.
9. **Issuing bank settles** with the advising bank and **releases the documents to the buyer**. The buyer needs these documents — crucially the **Bill of Lading** — to take possession of the goods from the carrier and clear customs. The issuing bank only releases them once the buyer has paid or obtained a loan from it.
10. **Advising bank credits the seller.** Process ends.

### 2.5 Why it works
- **Seller**: paid against documents, not against the buyer's goodwill. As long as the papers are compliant, the bank pays.
- **Buyer**: doesn't pay until the seller has demonstrably shipped — proof is in the documents. And physical possession is blocked until the issuing bank releases the Bill of Lading.
- **Bank**: takes a fee for guaranteeing. Its job is verifying well-defined documents, not trusting counterparties — a much cheaper risk.
- **Linchpin**: the Bill of Lading ties physical possession to documentary compliance. Carrier won't release cargo without the buyer's copy of the B/L; the buyer only gets that copy via the issuing bank after payment/credit.

### 2.6 Variants (for context, not the main exam answer)
- **Irrevocable vs. revocable** — modern LCs are irrevocable by default (can't be unilaterally cancelled).
- **Confirmed LC** — advising bank also guarantees payment, adding a second-bank layer of protection for the seller.
- **Transferable, back-to-back** — used in intermediated trades (brief mention).

## 3. Factoring

- **Definition**: selling your **accounts receivable** (customer invoices) to a third party — the **factor** (typically a division of a large bank) — at a discount, in exchange for immediate cash.
- **Purpose**: convert outstanding receivables into **immediate cash**. The #1 cause of business failure is cash-flow shortage: if invoices are due in 60–90 days but payroll is due now, factoring bridges the gap.
- **Economics**: typical deal — factor advances ~90–94 % of face value today, later collects the full 100 % from the debtor. On a $100,000 invoice, seller gets ~$94,000 today; the factor keeps the ~$6,000 spread as its fee for assuming collection risk.
- **Origin**: from French *facteur* (Paris) — not a mathematical factor.
- **Typical use**: fast-growing exporters without a balance sheet strong enough to carry long receivable cycles, especially those waiting on slow-paying foreign customers.

**LC vs. factoring — don't confuse them:**
- LC = guarantees payment *before* the sale happens; shifts **counterparty risk** to a bank.
- Factoring = monetises receivables *after* the sale has happened; shifts **cash-flow timing** (and some collection risk) to a factor.

## 4. Key terminology
| Term | Definition |
|---|---|
| Letter of Credit (LC) | Irrevocable promise of payment by the issuing (buyer's) bank to the seller, through the advising (seller's) bank, conditional on presentation of compliant documents within a specified time. |
| Applicant | The buyer — the party requesting the LC. |
| Beneficiary | The seller — the party entitled to be paid. |
| Issuing bank | Buyer's bank; issues the LC and is obligated to pay on compliant documents. |
| Advising bank (notifying bank) | Seller's bank; authenticates the LC and handles documents. Same role under either name. |
| Confirmed LC | Variant where the advising bank also guarantees payment. |
| Bill of Lading | Transport document that is both title to the goods and delivery receipt; the LC's enforceability hinges on it. |
| Factor | Third party (usually a bank division) that buys receivables at a discount for cash. |
| Factoring | Sale of receivables to a factor at a discount for immediate cash; a working-capital tool. |

## 5. Exam questions flagged

### Explicit
- **[EXAM]** *Control Question 4 (L22):* "Firms engaged in international trade must do business with people they cannot trust… How can each party protect themselves in these situations and how would such a defense work?" — answer centred on the LC mechanism (Hill **p. 474**).
- **[EXAM]** *L19:* Explain the functioning of a letter of credit — teacher flagged as "most likely on the exam… probably on the second exam".
- **[EXAM]** *L19 / L22:* Step-by-step flow of an LC — teacher said he will send an LC video before the exam for students to prepare.

### Likely
- **[LIKELY]** *L19:* Explain what factoring is — teacher stressed "I want you to know what factoring is"; conceptually simple, plausible short definitional question.
- **[LIKELY]** Differentiate LC from factoring — natural follow-up given both appear in the same lecture.

## 6. Connections
- Related topics:
  - [T06 — Export Plan 4Ps](T06%20-%20Export%20Plan%204Ps.md) — LC recommended for first sales under the *Promotion* P when buyer and seller don't know each other.
  - [T07 — Export Documents and Flow](T07%20-%20Export%20Documents%20and%20Flow.md) — the 5 required docs (invoice, Bill of Lading, pedimento, certificate of origin, packing list) are the compliant documents the LC turns on; the Bill of Lading in particular is the LC's enforcement linchpin.
  - [T08 — Incoterms](T08%20-%20Incoterms.md) — LC answers *who pays*; Incoterms answer *who delivers and when risk transfers*. Together they fully specify payment + delivery in the contract.
- Source lectures: [Lecture 19](../lectures/ADM-11013%20Lecture%2019.md), [Lecture 22](../lectures/ADM-11013%20Lecture%2022.md).

## 7. Watch out
- **"Advising bank" and "notifying bank" are the same role.** The transcript occasionally uses "notifying"; use "advising" in exam answers.
- **2-stage model is the class answer.** Real-world LCs can involve additional intermediaries and confirmation steps; the teacher's preferred answer is the simplified 2-stage, 10-step flow above.
- **Seller reviews terms in step 5 — don't skip this.** The entire guarantee collapses if the seller can't satisfy a condition and hasn't flagged it.
- **Timing of step 9.** Settlement to the advising bank and release of docs to the buyer are typically simultaneous in practice; don't over-index on ordering them.
- **LC ≠ factoring.** Different problems (trust vs. cash flow), different mechanics, different parties.
- **LC is for cross-border / untrusted.** It's overkill (and rare) in domestic trade with known counterparties.
