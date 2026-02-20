# STANDARD 007
**Standards for the Use of Transaction Codes and Return Reason Codes in AFT Files**

**Last updated:** July 1, 2025

---

## Scope
This standard defines the complete list of Transaction Codes and Return Reason Codes for use in Automated Funds Transfer (AFT) and ISO AFT payment transactions.

## Use of Standard
Read with:
- ACSS Rules Manual, Section F
- CPA Standard 005
- ISO AFT Usage Guidelines

---

# Appendix I

## Transaction Codes

### 000–149
- Unassigned

### 150–199
- Reserved for MICR Debits (Clearing Items)

---

## Pre-Authorized Transactions

### Payroll (200–229)
| code | description |
|---:|---|
| 200 | Payroll Deposit |
| 201 | Special Payroll |
| 202 | Vacation Payroll |
| 203 | Overtime Payroll |
| 204 | Advance Payroll |
| 205 | Commission Payroll |
| 206 | Bonus Payroll |
| 207 | Adjustment Payroll |

### Pension (230–239)
| code | description |
|---:|---|
| 230 | Pension |
| 231 | Federal Pension |
| 232 | Provincial Pension |
| 233 | Private Pension |

### Annuity (240–249)
| code | description |
|---:|---|
| 240 | Annuity |

### Dividend (250–259)
| code | description |
|---:|---|
| 250 | Dividend |
| 251 | Common Dividend |
| 252 | Preferred Dividend |

### Investments (260–279)
| code | description |
|---:|---|
| 260 | Investment |
| 261 | Mutual Funds |
| 265 | Spousal RSP Contribution |
| 266 | RESP Contribution |
| 271 | RSP Contribution |
| 272 | Retirement Income Fund |
| 273 | Tax Free Savings Account |
| 274 | RDSP Contribution |

### Interest and Lottery (280–299)
| code | description |
|---:|---|
| 280 | Interest |
| 281 | Lottery Prize Payment |

---

## Federal Government Transactions (For Federal Government Use Only)

### Federal Government (300–329)
| code | description |
|---:|---|
| 300 | Federal Payment |
| 301 | Agri Stabilization |
| 302 | AgriInvest |
| 303 | HRDC – Training |
| 308 | Canada Child Benefit |
| 309 | GST |
| 310 | CPP |
| 311 | Old Age Security |
| 312 | War Veterans’ Allow. |
| 313 | VAC |
| 315 | PS Superannuation |
| 316 | CF Superannuation |
| 317 | Tax Refund |
| 318 | EI |
| 319* | PAD CCRA |
| 320 | Student Loan |
| 321 | CSB Interest |
| 322 | External Affairs |
| 323 | Savings Plan |
| 324 | Access Grants |
| 325 | Canada Carbon Rebate |
| 326 | Canada Dental Benefit |
| 327 | Canada Workers Benefit |
| 328 | Canada Disability Benefit |

\* Debit transactions only. Not to be used for credit transactions.

---

## Pre-Authorized Transactions (Continued)

### Insurance (330–349)
| code | description |
|---:|---|
| 330 | Insurance |
| 331 | Life Insurance |
| 332 | Auto Insurance |
| 333 | Property Insurance |
| 334 | Casualty Insurance |
| 335 | Mortgage Insurance |
| 336 | Health/Dental Claim Insurance |

### Loans (350–369)
| code | description |
|---:|---|
| 350 | Loans |
| 351 | Personal Loans |
| 352 | Dealer Plan Loans |
| 353 | Farm Improvement Loans |
| 354 | Home Improvement Loans |
| 355 | Term Loans |
| 356 | Insurance Loans |

### Mortgage (370–379)
| code | description |
|---:|---|
| 370 | Mortgage |
| 371 | Residential Mortgage |
| 372 | Commercial Mortgage |
| 373 | Farm Mortgage |

### Taxes (380–399)
| code | description |
|---:|---|
| 380 | Taxes |
| 381 | Income Taxes |
| 382 | Sales Taxes |
| 383 | Corporate Taxes |
| 384 | School Taxes |
| 385 | Property Taxes |
| 386 | Water Taxes |

### Rent/Leases (400–419)
| code | description |
|---:|---|
| 400 | Rent/Leases |
| 401 | Residential Rent/Leases |
| 402 | Commercial Rent/Leases |
| 403 | Equipment Rent/Leases |
| 404 | Automobile Rent/Leases |
| 405 | Appliance Rent/Leases |

### Cash Management (420–429)
| code | description |
|---:|---|
| 420 | Cash Management |

### Bill Payment (430–449)
| code | description |
|---:|---|
| 430 | Bill Payment |
| 431 | Telephone Bill Payment |
| 432 | Gasoline Bill Payment |
| 433 | Hydro Bill Payment |
| 434 | Cable Bill Payment |
| 435 | Fuel Bill Payment |
| 436 | Utility Bill Payment |
| 437 | Internet Access Payment |
| 438 | Water Bill Payment |
| 439 | Auto Payment |

### Misc. Payments (450–599)
| code | description |
|---:|---|
| 450 | Misc. Payments |
| 451 | Customer Cheques |
| 452 | Expense Payment |
| 453 | Bill Payment Error Correction |
| 460 | Accounts Payable |
| 470 | Fees/Dues |
| 480 | Donations |

---

## Provincial and Local Government Transactions (600–620)

| code | description |
|---:|---|
| 600 | Prov./Local Gvt. Payment |
| 601 | Family Support Plan |
| 602 | Housing Allowance |
| 603 | Income Security Benefits |
| 604 | Family Ben. |
| 605 | Prov./Terr. |
| 606 | Workers’ Compensation Board |
| 607 | Employment Assistance Allowance |
| 608 | Automobile Insurance Plan |
| 609 | Health Care Premium |
| 610 | Offences and Fines |
| 611 | Disability Payment |
| 612 | Parental Insurance |
| 613 | Student Loan |
| 614 | Grant/Bursary |
| 615 | Solidarity Tax Credit |
| 616 | Children Assistance |
| 617 | Tax Refund |

### 621–649
- Unassigned (Future Use)

### 650*
| code | description |
|---:|---|
| 650* | Inter-FI Funds Transfer Debit |

\* Debit transactions only. Not to be used for credit transactions.

### 651–699
- Unassigned (Future Use)

---

## Commercial Pre-Authorized Debits (700–749)

### 700
| code | description |
|---:|---|
| 700 | Business PAD |

### 701–715
| code | description |
|---:|---|
| 701 | Commercial Investments |
| 702 | Commercial Insurance |
| 703 | Commercial Auto Insurance |
| 704 | Commercial Property Insurance |
| 705 | Commercial Casualty Insurance |
| 706 | Commercial Mortgage Insurance |
| 707 | Commercial Loans |
| 708 | Commercial Mortgage |
| 709 | Commercial Taxes |
| 710 | Commercial Income Taxes |
| 711 | Commercial Sales Taxes |
| 712 | Commercial GST |
| 713 | Commercial Property Taxes |
| 714 | Commercial Rent/Lease |
| 715 | Commercial Equipment Rent/Lease |

### 716–731
| code | description |
|---:|---|
| 716 | Commercial Automobile Rent/Lease |
| 717 | Commercial Cash Management |
| 718 | Commercial Bill Payment |
| 719 | Commercial Telephone Bill Payment |
| 720 | Commercial Gasoline Bill Payment |
| 721 | Commercial Hydro Bill Payment |
| 722 | Commercial Cable Bill Payment |
| 723 | Commercial Fuel Bill Payment |
| 724 | Commercial Utility Bill Payment |
| 725 | Commercial Internet Bill Payment |
| 726 | Commercial Water Bill Payment |
| 727 | Commercial Auto Payment |
| 728 | Commercial Expense Payment |
| 729 | Commercial Accounts Payable |
| 730 | Commercial Fees/Due |
| 731 | Commercial Creditor Insurance |

---

## Internal Direct Clearer Use (750–899)
- Internal use only (no codes listed)

---

# Return Reason Codes (900-series)

## FI Dishonoured Transaction (900–914)
| code | description |
|---:|---|
| 900 | Edit Reject |
| 901 | NSF (Debit Only) |
| 902 | Account not found |
| 903 | Payment Stopped/Recalled |
| 905 | Account Closed |
| 907 | No Debit Allowed |
| 908 | Funds Not Cleared (Debit Only) |
| 909 | Currency/Account Mismatch |
| 910 | Payor/Payee Deceased |
| 911 | Account Frozen |
| 912 | Invalid/Incorrect Account No. |
| 914 | Incorrect Payor/Payee Name |

## Customer Initiated Returns (Debits Only) (915–921)
| code | description |
|---:|---|
| 915 | No Agreement Existed |
| 916 | Not According to Agreement – Personal |
| 917 | Agreement Revoked – Personal |
| 918 | No Confirmation/Pre-Notification – Personal |
| 919 | Not According to Agreement – Business |
| 920 | Agreement Revoked – Business |
| 921 | No Confirmation/Pre-Notification – Business |

## Credit Return (Customer Initiated) (922)
| code | description |
|---:|---|
| 922 | Customer Initiated Return |

## Default (990)
| code | description |
|---:|---|
| 990 | Institution in Default |

---

## Notes
1. As at October 11, 2007, Transaction Code 906 has been retired and must not be reused except for “Account Transferred”.
2. In the range 200–699:
   - 2nd digit (tens) describes the generic payment type
   - 3rd digit (units) allows finer breakdown
3. The abbreviation mnemonic is a suggested minimum three-character description. Direct Clearers may expand it if they stay within the generic type.
4. All 700-series transaction types carry a recourse period of 10 business days, except code 717 (Cash Management), which has no recourse per Rule H1.
5. Transaction Codes 915 and 922 may also be used to return an Error Correction (credit or debit respectively) being refused by the Payor or Payee.
