## Sheet: README

| Row | Lumivaara Logistics Oy - Operational data extract for FAIR AI assessment |
| --- | --- |
| 2 | Prepared by: Jari Koskela, IT Manager. Extract date: 9 October 2026. |
| 3 | Fictional example company - all data is synthetic and created for report-generation testing. |
| 5 | Sheets |
| 6 | Monthly_Volumes - monthly volumes and effort per site, Jan 2024 - Sep 2026 (WMS + TMS + payroll). |
| 7 | Daily_Volumes_Sep2026 - daily inbound/outbound/document volumes per site for September 2026. |
| 8 | Document_Log_Sample - 150 freight documents logged during a one-week time study in Vantaa, Tampere and Oulu (28 Sep - 2 Oct 2026). |
| 9 | CS_Email_Tally - customer service mailbox category tally (one tally week per month), Apr - Sep 2026. |
| 10 | Data_Inventory - systems and datasets relevant to the AI use cases. |
| 11 | Use_Case_Scoring - management team's preliminary scoring of AI use cases (1 = low, 5 = high). |
| 13 | Notes and caveats |
| 14 | - freight_docs_received counts documents registered in the TMS document log; paper documents scanned in batches are registered on the scan date. |
| 15 | - WMS data before 2020 is not included: the WMS database structure changed in the 2020 upgrade. |
| 16 | - Oulu warehouse data starts from its opening in 2023; only 2024 onwards is included here. |
| 17 | - Overtime cost includes statutory overtime premiums; agency staff days are billed days from the staffing agency. |
| 18 | - entry_errors = documents for which a correction was later made in TMS or Business Central. |

## Sheet: Monthly_Volumes

| Row | month | site | working_days | inbound_pallets | outbound_order_lines | shipments | freight_docs_received | doc_manual_entry_hours | entry_errors | overtime_hours | overtime_cost_eur | agency_staff_days |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | 2024-01 | Vantaa | 23 | 6603 | 102881 | 8733 | 10860 | 508.6 | 376 | 218 | 12349 | 43 |
| 3 | 2024-01 | Tampere | 23 | 3496 | 47369 | 4624 | 4591 | 219.5 | 148 | 185 | 10479 | 17 |
| 4 | 2024-01 | Oulu | 23 | 1451 | 19663 | 1919 | 2654 | 130.9 | 102 | 43 | 2436 | 8 |
| 5 | 2024-02 | Vantaa | 21 | 6952 | 108317 | 9194 | 10182 | 512.9 | 411 | 212 | 12009 | 37 |
| 6 | 2024-02 | Tampere | 21 | 3706 | 50214 | 4901 | 4425 | 201.9 | 146 | 247 | 13991 | 19 |
| 7 | 2024-02 | Oulu | 21 | 1667 | 22598 | 2206 | 2629 | 127.7 | 114 | 58 | 3285 | 8 |
| 8 | 2024-03 | Vantaa | 21 | 7557 | 117749 | 9995 | 11750 | 596.3 | 457 | 280 | 15861 | 44 |
| 9 | 2024-03 | Tampere | 21 | 2690 | 36452 | 3558 | 4774 | 217.4 | 166 | 113 | 6401 | 21 |
| 10 | 2024-03 | Oulu | 21 | 1766 | 23936 | 2336 | 2749 | 130.5 | 94 | 63 | 3569 | 12 |
| 11 | 2024-04 | Vantaa | 22 | 7493 | 116759 | 9911 | 12498 | 576.7 | 509 | 232 | 13142 | 53 |
| 12 | 2024-04 | Tampere | 22 | 4143 | 56136 | 5479 | 5265 | 256.5 | 211 | 305 | 17277 | 27 |
| 13 | 2024-04 | Oulu | 22 | 1695 | 22966 | 2242 | 2828 | 133.2 | 99 | 57 | 3229 | 13 |
| 14 | 2024-05 | Vantaa | 23 | 7932 | 123594 | 10491 | 13020 | 642.8 | 478 | 321 | 18183 | 59 |
| 15 | 2024-05 | Tampere | 23 | 2876 | 38974 | 3804 | 5430 | 264.7 | 190 | 147 | 8327 | 30 |
| 16 | 2024-05 | Oulu | 23 | 1783 | 24157 | 2358 | 3094 | 159.8 | 117 | 60 | 3399 | 9 |
| 17 | 2024-06 | Vantaa | 20 | 6806 | 106056 | 9002 | 11163 | 561.3 | 413 | 182 | 10309 | 49 |
| 18 | 2024-06 | Tampere | 20 | 4075 | 55217 | 5390 | 4643 | 239 | 196 | 222 | 12575 | 24 |
| 19 | 2024-06 | Oulu | 20 | 1772 | 24008 | 2343 | 2655 | 124.2 | 105 | 58 | 3285 | 10 |
| 20 | 2024-07 | Vantaa | 23 | 5907 | 92044 | 7813 | 10943 | 556.3 | 384 | 149 | 8440 | 24 |
| 21 | 2024-07 | Tampere | 23 | 3240 | 43904 | 4285 | 4559 | 214.2 | 180 | 162 | 9177 | 10 |
| 22 | 2024-07 | Oulu | 23 | 1479 | 20045 | 1956 | 2522 | 126.6 | 96 | 37 | 2096 | 5 |
| 23 | 2024-08 | Vantaa | 22 | 6865 | 106966 | 9079 | 12926 | 657.4 | 542 | 198 | 11216 | 43 |
| 24 | 2024-08 | Tampere | 22 | 3947 | 53477 | 5220 | 5438 | 247.8 | 205 | 210 | 11896 | 25 |
| 25 | 2024-08 | Oulu | 22 | 1832 | 24824 | 2423 | 2864 | 138 | 110 | 64 | 3625 | 12 |
| 26 | 2024-09 | Vantaa | 21 | 7856 | 122416 | 10391 | 12398 | 602.5 | 505 | 248 | 14048 | 60 |
| 27 | 2024-09 | Tampere | 21 | 4493 | 60881 | 5943 | 5442 | 260.8 | 207 | 275 | 15578 | 25 |
| 28 | 2024-09 | Oulu | 21 | 1862 | 25240 | 2463 | 3091 | 143.8 | 107 | 62 | 3512 | 13 |
| 29 | 2024-10 | Vantaa | 23 | 7908 | 123216 | 10459 | 15058 | 763.9 | 494 | 254 | 14388 | 76 |
| 30 | 2024-10 | Tampere | 23 | 3033 | 41094 | 4011 | 5854 | 299.9 | 227 | 152 | 8610 | 34 |
| 31 | 2024-10 | Oulu | 23 | 2057 | 27879 | 2721 | 3365 | 153.6 | 125 | 84 | 4758 | 14 |
| 32 | 2024-11 | Vantaa | 21 | 10222 | 159268 | 13519 | 16196 | 835.1 | 537 | 452 | 25604 | 115 |
| 33 | 2024-11 | Tampere | 21 | 5270 | 71408 | 6970 | 6518 | 301.6 | 243 | 430 | 24358 | 48 |
| 34 | 2024-11 | Oulu | 21 | 2293 | 31077 | 3033 | 3982 | 191 | 168 | 113 | 6401 | 20 |
| 35 | 2024-12 | Vantaa | 22 | 11159 | 173879 | 14759 | 18155 | 934.3 | 782 | 607 | 34384 | 122 |
| 36 | 2024-12 | Tampere | 22 | 4562 | 61811 | 6033 | 7166 | 341.6 | 234 | 330 | 18693 | 73 |
| 37 | 2024-12 | Oulu | 22 | 2421 | 32802 | 3202 | 4335 | 208.2 | 160 | 140 | 7930 | 33 |
| 38 | 2025-01 | Vantaa | 23 | 6981 | 108775 | 9233 | 12462 | 573.7 | 443 | 261 | 14784 | 42 |
| 39 | 2025-01 | Tampere | 23 | 3128 | 42387 | 4137 | 5249 | 238.2 | 204 | 168 | 9516 | 20 |
| 40 | 2025-01 | Oulu | 23 | 1582 | 21444 | 2093 | 3061 | 139.4 | 104 | 57 | 3229 | 8 |
| 41 | 2025-02 | Vantaa | 20 | 6860 | 106886 | 9073 | 10491 | 534.4 | 366 | 228 | 12915 | 45 |
| 42 | 2025-02 | Tampere | 20 | 2996 | 40601 | 3963 | 4619 | 224 | 199 | 142 | 8044 | 20 |
| 43 | 2025-02 | Oulu | 20 | 1647 | 22318 | 2178 | 2590 | 128.1 | 92 | 56 | 3172 | 9 |
| 44 | 2025-03 | Vantaa | 21 | 7258 | 113099 | 9600 | 12359 | 638.4 | 543 | 218 | 12349 | 48 |
| 45 | 2025-03 | Tampere | 21 | 2948 | 39942 | 3899 | 5438 | 276.6 | 231 | 148 | 8384 | 20 |
| 46 | 2025-03 | Oulu | 21 | 1939 | 26278 | 2565 | 3039 | 149.1 | 133 | 86 | 4872 | 8 |
| 47 | 2025-04 | Vantaa | 22 | 8191 | 127634 | 10834 | 12943 | 639.7 | 560 | 275 | 15578 | 47 |
| 48 | 2025-04 | Tampere | 22 | 2682 | 36340 | 3547 | 5577 | 261.1 | 218 | 138 | 7817 | 21 |
| 49 | 2025-04 | Oulu | 22 | 1917 | 25983 | 2536 | 3095 | 149.4 | 132 | 88 | 4985 | 9 |
| 50 | 2025-05 | Vantaa | 22 | 7961 | 124045 | 10529 | 13249 | 596.5 | 546 | 305 | 17277 | 54 |
| 51 | 2025-05 | Tampere | 22 | 4038 | 54711 | 5340 | 5721 | 273.8 | 183 | 235 | 13312 | 29 |
| 52 | 2025-05 | Oulu | 22 | 2040 | 27647 | 2698 | 3267 | 165.2 | 127 | 79 | 4475 | 10 |
| 53 | 2025-06 | Vantaa | 21 | 7480 | 116552 | 9893 | 12849 | 646.4 | 543 | 285 | 16144 | 45 |
| 54 | 2025-06 | Tampere | 21 | 2904 | 39354 | 3841 | 4983 | 250.2 | 212 | 140 | 7930 | 23 |
| 55 | 2025-06 | Oulu | 21 | 1755 | 23786 | 2321 | 3092 | 157 | 135 | 72 | 4078 | 11 |
| 56 | 2025-07 | Vantaa | 23 | 5923 | 92290 | 7834 | 11435 | 539.9 | 493 | 167 | 9460 | 32 |
| 57 | 2025-07 | Tampere | 23 | 3295 | 44646 | 4358 | 4582 | 230.2 | 152 | 184 | 10423 | 14 |
| 58 | 2025-07 | Oulu | 23 | 1463 | 19831 | 1935 | 2766 | 133 | 98 | 47 | 2662 | 5 |
| 59 | 2025-08 | Vantaa | 21 | 7328 | 114182 | 9692 | 12234 | 577.3 | 518 | 275 | 15578 | 48 |
| 60 | 2025-08 | Tampere | 21 | 3742 | 50708 | 4950 | 5247 | 270.4 | 201 | 254 | 14388 | 19 |
| 61 | 2025-08 | Oulu | 21 | 2008 | 27213 | 2656 | 2931 | 150.7 | 103 | 73 | 4135 | 10 |
| 62 | 2025-09 | Vantaa | 22 | 8740 | 136188 | 11560 | 13997 | 686.4 | 533 | 326 | 18466 | 67 |
| 63 | 2025-09 | Tampere | 22 | 3211 | 43513 | 4247 | 6115 | 275.2 | 263 | 176 | 9970 | 30 |
| 64 | 2025-09 | Oulu | 22 | 2101 | 28473 | 2779 | 3481 | 165.1 | 114 | 96 | 5438 | 12 |
| 65 | 2025-10 | Vantaa | 23 | 8534 | 132977 | 11287 | 15964 | 795 | 568 | 306 | 17334 | 68 |
| 66 | 2025-10 | Tampere | 23 | 3648 | 49438 | 4826 | 6347 | 291 | 235 | 248 | 14048 | 33 |
| 67 | 2025-10 | Oulu | 23 | 2221 | 30101 | 2938 | 3745 | 176 | 144 | 86 | 4872 | 13 |
| 68 | 2025-11 | Vantaa | 20 | 10451 | 162838 | 13822 | 16287 | 804 | 612 | 488 | 27643 | 108 |
| 69 | 2025-11 | Tampere | 20 | 4583 | 62097 | 6061 | 7058 | 355.1 | 240 | 307 | 17390 | 53 |
| 70 | 2025-11 | Oulu | 20 | 2580 | 34959 | 3412 | 3814 | 192.4 | 156 | 148 | 8384 | 21 |
| 71 | 2025-12 | Vantaa | 23 | 10643 | 165839 | 14077 | 18632 | 868.9 | 702 | 573 | 32455 | 117 |
| 72 | 2025-12 | Tampere | 23 | 4660 | 63146 | 6164 | 8323 | 385.3 | 335 | 365 | 20676 | 54 |
| 73 | 2025-12 | Oulu | 23 | 2725 | 36921 | 3604 | 4462 | 223.1 | 184 | 138 | 7817 | 27 |
| 74 | 2026-01 | Vantaa | 22 | 7043 | 109738 | 9315 | 12993 | 629.6 | 423 | 217 | 12292 | 46 |
| 75 | 2026-01 | Tampere | 22 | 3172 | 42985 | 4196 | 5375 | 265.8 | 235 | 179 | 10140 | 20 |
| 76 | 2026-01 | Oulu | 22 | 1867 | 25305 | 2470 | 3015 | 150.1 | 114 | 83 | 4702 | 8 |
| 77 | 2026-02 | Vantaa | 20 | 8007 | 124754 | 10589 | 11895 | 572.9 | 417 | 273 | 15464 | 46 |
| 78 | 2026-02 | Tampere | 20 | 3853 | 52204 | 5096 | 4887 | 240.3 | 172 | 216 | 12235 | 17 |
| 79 | 2026-02 | Oulu | 20 | 1762 | 23875 | 2330 | 2736 | 133 | 92 | 63 | 3569 | 9 |
| 80 | 2026-03 | Vantaa | 22 | 8455 | 131738 | 11182 | 13235 | 631.5 | 509 | 324 | 18353 | 48 |
| 81 | 2026-03 | Tampere | 22 | 3458 | 46859 | 4574 | 6047 | 295.7 | 243 | 230 | 13028 | 26 |
| 82 | 2026-03 | Oulu | 22 | 1939 | 26273 | 2564 | 3157 | 149.5 | 129 | 91 | 5155 | 12 |
| 83 | 2026-04 | Vantaa | 22 | 8250 | 128554 | 10912 | 14401 | 700.5 | 565 | 290 | 16427 | 50 |
| 84 | 2026-04 | Tampere | 22 | 3545 | 48034 | 4689 | 5624 | 265.7 | 225 | 210 | 11896 | 21 |
| 85 | 2026-04 | Oulu | 22 | 1993 | 27012 | 2636 | 3247 | 159.6 | 104 | 84 | 4758 | 11 |
| 86 | 2026-05 | Vantaa | 21 | 7993 | 124536 | 10571 | 13955 | 640.6 | 523 | 258 | 14615 | 57 |
| 87 | 2026-05 | Tampere | 21 | 3152 | 42716 | 4169 | 5678 | 284.3 | 207 | 188 | 10649 | 29 |
| 88 | 2026-05 | Oulu | 21 | 1983 | 26867 | 2622 | 3164 | 142.8 | 121 | 98 | 5551 | 11 |
| 89 | 2026-06 | Vantaa | 22 | 8345 | 130024 | 11037 | 14150 | 698.2 | 580 | 356 | 20166 | 45 |
| 90 | 2026-06 | Tampere | 22 | 2616 | 35450 | 3460 | 5579 | 255.7 | 223 | 123 | 6967 | 19 |
| 91 | 2026-06 | Oulu | 22 | 2016 | 27319 | 2666 | 3391 | 156.4 | 133 | 92 | 5211 | 8 |
| 92 | 2026-07 | Vantaa | 23 | 7046 | 109790 | 9319 | 12426 | 568.1 | 401 | 200 | 11329 | 30 |
| 93 | 2026-07 | Tampere | 23 | 3753 | 50851 | 4964 | 4935 | 245.6 | 162 | 224 | 12689 | 12 |
| 94 | 2026-07 | Oulu | 23 | 1528 | 20709 | 2021 | 2927 | 148.3 | 114 | 42 | 2379 | 6 |
| 95 | 2026-08 | Vantaa | 21 | 8673 | 135145 | 11471 | 13207 | 632 | 481 | 332 | 18806 | 49 |
| 96 | 2026-08 | Tampere | 21 | 4414 | 59810 | 5838 | 5814 | 265.7 | 253 | 319 | 18070 | 26 |
| 97 | 2026-08 | Oulu | 21 | 2060 | 27918 | 2725 | 3198 | 159.6 | 139 | 82 | 4645 | 11 |
| 98 | 2026-09 | Vantaa | 22 | 9045 | 140933 | 11963 | 15126 | 724.6 | 616 | 339 | 19203 | 74 |
| 99 | 2026-09 | Tampere | 22 | 4717 | 63917 | 6239 | 6100 | 310.4 | 213 | 348 | 19713 | 29 |
| 100 | 2026-09 | Oulu | 22 | 2122 | 28760 | 2807 | 3464 | 175.5 | 118 | 86 | 4872 | 14 |

## Sheet: Daily_Volumes_Sep2026

| Row | date | weekday | site | inbound_pallets | outbound_order_lines | freight_docs_received | agency_workers | note |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | 2026-09-01 | Tue | Vantaa | 440 | 5937 | 559 | 0 |  |
| 3 | 2026-09-01 | Tue | Tampere | 171 | 2285 | 256 | 3 |  |
| 4 | 2026-09-01 | Tue | Oulu | 108 | 1149 | 135 | 2 | Customer forecast received |
| 5 | 2026-09-02 | Wed | Vantaa | 439 | 5689 | 571 | 5 |  |
| 6 | 2026-09-02 | Wed | Tampere | 187 | 2190 | 233 | 1 | Customer forecast received |
| 7 | 2026-09-02 | Wed | Oulu | 92 | 1449 | 130 | 1 |  |
| 8 | 2026-09-03 | Thu | Vantaa | 502 | 5641 | 560 | 0 | Customer forecast received |
| 9 | 2026-09-03 | Thu | Tampere | 175 | 2212 | 267 | 1 | Customer forecast received |
| 10 | 2026-09-03 | Thu | Oulu | 85 | 1523 | 149 | 4 | Customer forecast received |
| 11 | 2026-09-04 | Fri | Vantaa | 351 | 5564 | 571 | 5 | Customer forecast received |
| 12 | 2026-09-04 | Fri | Tampere | 316 | 2045 | 251 | 8 |  |
| 13 | 2026-09-04 | Fri | Oulu | 98 | 1525 | 126 | 1 |  |
| 14 | 2026-09-07 | Mon | Vantaa | 427 | 5798 | 649 | 2 |  |
| 15 | 2026-09-07 | Mon | Tampere | 193 | 2697 | 237 | 9 |  |
| 16 | 2026-09-07 | Mon | Oulu | 120 | 1226 | 131 | 3 | Customer forecast received |
| 17 | 2026-09-08 | Tue | Vantaa | 354 | 4764 | 591 | 3 | Customer forecast received |
| 18 | 2026-09-08 | Tue | Tampere | 172 | 2198 | 279 | 1 | Customer forecast received |
| 19 | 2026-09-08 | Tue | Oulu | 101 | 1380 | 157 | 1 | Customer forecast received |
| 20 | 2026-09-09 | Wed | Vantaa | 366 | 5206 | 535 | 0 |  |
| 21 | 2026-09-09 | Wed | Tampere | 94 | 2400 | 236 | 1 |  |
| 22 | 2026-09-09 | Wed | Oulu | 119 | 1344 | 143 | 0 | Customer forecast received |
| 23 | 2026-09-10 | Thu | Vantaa | 406 | 5180 | 526 | 5 |  |
| 24 | 2026-09-10 | Thu | Tampere | 91 | 2013 | 272 | 12 |  |
| 25 | 2026-09-10 | Thu | Oulu | 104 | 1351 | 141 | 1 |  |
| 26 | 2026-09-11 | Fri | Vantaa | 448 | 6388 | 594 | 2 |  |
| 27 | 2026-09-11 | Fri | Tampere | 193 | 2231 | 266 | 4 |  |
| 28 | 2026-09-11 | Fri | Oulu | 114 | 1325 | 135 | 1 |  |
| 29 | 2026-09-14 | Mon | Vantaa | 418 | 6420 | 628 | 3 |  |
| 30 | 2026-09-14 | Mon | Tampere | 181 | 2438 | 251 | 6 | Customer forecast received |
| 31 | 2026-09-14 | Mon | Oulu | 88 | 1258 | 160 | 2 | Customer forecast received |
| 32 | 2026-09-15 | Tue | Vantaa | 473 | 5952 | 565 | 0 |  |
| 33 | 2026-09-15 | Tue | Tampere | 198 | 2643 | 249 | 1 |  |
| 34 | 2026-09-15 | Tue | Oulu | 107 | 1347 | 134 | 5 |  |
| 35 | 2026-09-16 | Wed | Vantaa | 401 | 5404 | 675 | 3 |  |
| 36 | 2026-09-16 | Wed | Tampere | 172 | 2556 | 245 | 14 |  |
| 37 | 2026-09-16 | Wed | Oulu | 108 | 1262 | 147 | 5 |  |
| 38 | 2026-09-17 | Thu | Vantaa | 387 | 5339 | 609 | 3 |  |
| 39 | 2026-09-17 | Thu | Tampere | 193 | 2691 | 232 | 5 |  |
| 40 | 2026-09-17 | Thu | Oulu | 96 | 1333 | 161 | 2 |  |
| 41 | 2026-09-18 | Fri | Vantaa | 481 | 5015 | 683 | 0 |  |
| 42 | 2026-09-18 | Fri | Tampere | 193 | 2616 | 247 | 7 |  |
| 43 | 2026-09-18 | Fri | Oulu | 108 | 1406 | 129 | 2 |  |
| 44 | 2026-09-21 | Mon | Vantaa | 424 | 5851 | 663 | 5 |  |
| 45 | 2026-09-21 | Mon | Tampere | 374 | 2441 | 281 | 7 |  |
| 46 | 2026-09-21 | Mon | Oulu | 101 | 1418 | 134 | 1 | Customer forecast received |
| 47 | 2026-09-22 | Tue | Vantaa | 517 | 5942 | 528 | 0 | Customer forecast received |
| 48 | 2026-09-22 | Tue | Tampere | 164 | 2560 | 236 | 5 | Customer forecast received |
| 49 | 2026-09-22 | Tue | Oulu | 105 | 1461 | 129 | 0 |  |
| 50 | 2026-09-23 | Wed | Vantaa | 422 | 6293 | 535 | 2 | Customer forecast received |
| 51 | 2026-09-23 | Wed | Tampere | 186 | 2633 | 249 | 4 |  |
| 52 | 2026-09-23 | Wed | Oulu | 98 | 1540 | 135 | 5 |  |
| 53 | 2026-09-24 | Thu | Vantaa | 407 | 6438 | 663 | 0 |  |
| 54 | 2026-09-24 | Thu | Tampere | 183 | 2699 | 236 | 14 |  |
| 55 | 2026-09-24 | Thu | Oulu | 97 | 1418 | 154 | 0 |  |
| 56 | 2026-09-25 | Fri | Vantaa | 464 | 5240 | 653 | 3 |  |
| 57 | 2026-09-25 | Fri | Tampere | 184 | 2477 | 268 | 9 |  |
| 58 | 2026-09-25 | Fri | Oulu | 115 | 1403 | 135 | 2 |  |
| 59 | 2026-09-28 | Mon | Vantaa | 422 | 5255 | 644 | 1 | Customer forecast received |
| 60 | 2026-09-28 | Mon | Tampere | 97 | 2257 | 252 | 4 | Customer forecast received |
| 61 | 2026-09-28 | Mon | Oulu | 126 | 1532 | 135 | 5 |  |
| 62 | 2026-09-29 | Tue | Vantaa | 389 | 6026 | 550 | 4 |  |
| 63 | 2026-09-29 | Tue | Tampere | 375 | 2566 | 241 | 11 | Customer forecast received |
| 64 | 2026-09-29 | Tue | Oulu | 103 | 1413 | 151 | 3 |  |
| 65 | 2026-09-30 | Wed | Vantaa | 448 | 5152 | 514 | 5 |  |
| 66 | 2026-09-30 | Wed | Tampere | 85 | 2043 | 276 | 13 |  |
| 67 | 2026-09-30 | Wed | Oulu | 93 | 1523 | 135 | 2 | Customer forecast received |

## Sheet: Document_Log_Sample

| Row | doc_id | processed_at | site | doc_type | channel | language | handwritten_remarks | image_quality | pages | processing_minutes | entry_error | error_field | days_from_delivery_to_processing |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | D-26093001 | 2026-10-01 07:41 | Oulu | POD | Driver app photo | English | N | poor | 1 | 3.6 | N |  | 0 |
| 3 | D-26093002 | 2026-09-28 12:16 | Tampere | CMR waybill | Paper scan | Finnish | N | good | 1 | 2.4 | N |  | 6 |
| 4 | D-26093003 | 2026-10-02 06:21 | Vantaa | Customs document | Email PDF | Finnish | N | good | 7 | 6 | N |  | 1 |
| 5 | D-26093004 | 2026-09-30 08:31 | Vantaa | POD | Paper scan | Estonian | Y | poor | 1 | 5.3 | N |  | 4 |
| 6 | D-26093005 | 2026-09-29 06:15 | Tampere | CMR waybill | Email PDF | Lithuanian | N | good | 1 | 3.6 | N |  | 0 |
| 7 | D-26093006 | 2026-10-01 12:10 | Vantaa | Delivery note | Driver app photo | Finnish | N | good | 4 | 4 | N |  | 1 |
| 8 | D-26093007 | 2026-09-28 07:02 | Vantaa | POD | Driver app photo | Lithuanian | Y | fair | 1 | 4.5 | N |  | 1 |
| 9 | D-26093008 | 2026-09-30 15:59 | Oulu | Delivery note | Driver app photo | Finnish | N | good | 1 | 2.3 | N |  | 0 |
| 10 | D-26093009 | 2026-09-29 13:20 | Vantaa | POD | Paper scan | Finnish | N | fair | 1 | 1.9 | N |  | 9 |
| 11 | D-26093010 | 2026-09-29 14:05 | Vantaa | POD | Email PDF | Finnish | N | good | 1 | 2.4 | N |  | 2 |
| 12 | D-26093011 | 2026-09-28 13:00 | Vantaa | Delivery note | Email PDF | Finnish | N | fair | 1 | 2.6 | N |  | 2 |
| 13 | D-26093012 | 2026-09-29 14:13 | Vantaa | Delivery note | Paper scan | Estonian | N | poor | 3 | 5.2 | N |  | 4 |
| 14 | D-26093013 | 2026-10-02 15:30 | Vantaa | POD | Paper scan | Finnish | N | fair | 1 | 2.9 | N |  | 10 |
| 15 | D-26093014 | 2026-09-29 15:39 | Vantaa | Packing list | Paper scan | Finnish | N | fair | 3 | 4.1 | N |  | 3 |
| 16 | D-26093015 | 2026-09-30 11:19 | Tampere | POD | Paper scan | Lithuanian | Y | fair | 1 | 3.8 | N |  | 3 |
| 17 | D-26093016 | 2026-10-01 13:32 | Tampere | Delivery note | Driver app photo | Finnish | Y | good | 1 | 3.5 | N |  | 1 |
| 18 | D-26093017 | 2026-09-28 09:45 | Vantaa | POD | Driver app photo | Finnish | Y | fair | 1 | 3.4 | N |  | 1 |
| 19 | D-26093018 | 2026-10-01 13:20 | Vantaa | CMR waybill | Email PDF | Finnish | Y | good | 1 | 3 | N |  | 0 |
| 20 | D-26093019 | 2026-10-01 06:19 | Vantaa | CMR waybill | Driver app photo | Finnish | N | fair | 1 | 1.9 | N |  | 0 |
| 21 | D-26093020 | 2026-09-29 13:51 | Vantaa | POD | Email PDF | Finnish | N | good | 1 | 2.2 | N |  | 2 |
| 22 | D-26093021 | 2026-09-29 11:41 | Tampere | Packing list | Email PDF | Estonian | N | good | 1 | 3.1 | N |  | 2 |
| 23 | D-26093022 | 2026-09-29 07:45 | Tampere | POD | Driver app photo | Finnish | Y | fair | 1 | 3.1 | N |  | 0 |
| 24 | D-26093023 | 2026-10-02 11:30 | Vantaa | POD | Driver app photo | Swedish | N | good | 1 | 3.6 | N |  | 1 |
| 25 | D-26093024 | 2026-09-30 13:52 | Oulu | CMR waybill | Email PDF | Finnish | N | good | 1 | 2.2 | N |  | 0 |
| 26 | D-26093025 | 2026-10-02 15:27 | Vantaa | POD | Paper scan | Finnish | N | poor | 1 | 3.9 | N |  | 8 |
| 27 | D-26093026 | 2026-09-28 11:51 | Oulu | Delivery note | Email PDF | Polish | N | good | 4 | 4.7 | N |  | 3 |
| 28 | D-26093027 | 2026-09-30 10:49 | Oulu | POD | Driver app photo | Finnish | N | poor | 1 | 3.7 | N |  | 1 |
| 29 | D-26093028 | 2026-09-30 08:33 | Vantaa | Delivery note | Driver app photo | Finnish | N | good | 3 | 2.9 | N |  | 1 |
| 30 | D-26093029 | 2026-09-30 15:32 | Vantaa | CMR waybill | Email PDF | Finnish | N | good | 1 | 2.3 | N |  | 0 |
| 31 | D-26093030 | 2026-09-28 12:11 | Vantaa | Delivery note | Paper scan | English | N | fair | 1 | 2.7 | N |  | 6 |
| 32 | D-26093031 | 2026-10-02 15:12 | Vantaa | Customs document | Email PDF | Swedish | N | fair | 2 | 3.1 | N |  | 0 |
| 33 | D-26093032 | 2026-10-01 06:44 | Tampere | Packing list | Email PDF | Finnish | N | good | 4 | 3.5 | N |  | 1 |
| 34 | D-26093033 | 2026-09-29 12:16 | Vantaa | Delivery note | Email PDF | Finnish | N | good | 4 | 3.6 | N |  | 3 |
| 35 | D-26093034 | 2026-10-02 08:21 | Tampere | CMR waybill | Driver app photo | Swedish | N | fair | 1 | 3.1 | N |  | 0 |
| 36 | D-26093035 | 2026-09-29 10:39 | Oulu | POD | Driver app photo | Finnish | N | fair | 1 | 2.5 | N |  | 0 |
| 37 | D-26093036 | 2026-09-28 12:45 | Vantaa | CMR waybill | Paper scan | Finnish | N | fair | 1 | 3 | N |  | 7 |
| 38 | D-26093037 | 2026-09-29 06:39 | Vantaa | POD | Paper scan | Finnish | Y | poor | 1 | 5 | N |  | 3 |
| 39 | D-26093038 | 2026-10-02 15:00 | Vantaa | Delivery note | Driver app photo | Finnish | N | good | 1 | 3.1 | Y | package count | 0 |
| 40 | D-26093039 | 2026-10-02 15:08 | Vantaa | Delivery note | Email PDF | Finnish | N | good | 4 | 3.4 | N |  | 3 |
| 41 | D-26093040 | 2026-10-02 12:09 | Vantaa | CMR waybill | Email PDF | Finnish | N | good | 1 | 2.1 | N |  | 0 |
| 42 | D-26093041 | 2026-09-30 06:16 | Vantaa | CMR waybill | Driver app photo | Lithuanian | N | good | 1 | 3.2 | N |  | 1 |
| 43 | D-26093042 | 2026-10-02 11:46 | Vantaa | POD | Email PDF | English | Y | good | 1 | 3.7 | N |  | 2 |
| 44 | D-26093043 | 2026-09-28 11:00 | Tampere | POD | Paper scan | Finnish | N | fair | 1 | 2.9 | N |  | 8 |
| 45 | D-26093044 | 2026-09-30 12:05 | Vantaa | Delivery note | Paper scan | Finnish | N | good | 4 | 3.7 | N |  | 4 |
| 46 | D-26093045 | 2026-09-30 09:11 | Oulu | POD | Driver app photo | Finnish | N | good | 1 | 2.4 | N |  | 1 |
| 47 | D-26093046 | 2026-10-02 11:00 | Vantaa | CMR waybill | Paper scan | Finnish | N | fair | 1 | 1.9 | N |  | 3 |
| 48 | D-26093047 | 2026-09-30 13:25 | Vantaa | POD | Driver app photo | Finnish | N | good | 1 | 2.8 | N |  | 0 |
| 49 | D-26093048 | 2026-09-29 13:28 | Vantaa | Customs document | Paper scan | Finnish | N | good | 7 | 5.8 | N |  | 1 |
| 50 | D-26093049 | 2026-09-30 13:34 | Vantaa | POD | Paper scan | Finnish | N | fair | 1 | 2.6 | N |  | 6 |
| 51 | D-26093050 | 2026-10-02 12:36 | Tampere | CMR waybill | Driver app photo | Finnish | N | good | 1 | 2 | N |  | 1 |
| 52 | D-26093051 | 2026-09-28 08:18 | Oulu | POD | Paper scan | Swedish | Y | fair | 1 | 4.3 | N |  | 4 |
| 53 | D-26093052 | 2026-09-28 15:23 | Tampere | CMR waybill | Paper scan | Finnish | Y | fair | 1 | 3.8 | N |  | 6 |
| 54 | D-26093053 | 2026-09-29 10:02 | Vantaa | Packing list | Paper scan | Swedish | N | fair | 3 | 4.2 | N |  | 4 |
| 55 | D-26093054 | 2026-10-01 14:10 | Tampere | POD | Driver app photo | Finnish | N | fair | 1 | 2.7 | N |  | 1 |
| 56 | D-26093055 | 2026-10-02 09:06 | Vantaa | Delivery note | Paper scan | Finnish | N | fair | 4 | 4 | N |  | 3 |
| 57 | D-26093056 | 2026-09-30 14:51 | Tampere | POD | Driver app photo | Estonian | N | fair | 1 | 2.9 | N |  | 0 |
| 58 | D-26093057 | 2026-10-02 15:54 | Oulu | Delivery note | Email PDF | English | N | good | 3 | 3.7 | N |  | 1 |
| 59 | D-26093058 | 2026-09-29 15:45 | Vantaa | Delivery note | Driver app photo | English | N | fair | 1 | 1.9 | N |  | 1 |
| 60 | D-26093059 | 2026-09-30 13:44 | Vantaa | CMR waybill | Driver app photo | English | Y | poor | 1 | 4.5 | N |  | 1 |
| 61 | D-26093060 | 2026-10-01 08:13 | Vantaa | POD | Driver app photo | Finnish | Y | fair | 1 | 3 | N |  | 1 |
| 62 | D-26093061 | 2026-09-29 08:43 | Tampere | CMR waybill | Email PDF | Finnish | Y | good | 1 | 2.8 | Y | remarks not entered | 3 |
| 63 | D-26093062 | 2026-09-28 12:42 | Tampere | Packing list | Driver app photo | Finnish | N | poor | 4 | 5.2 | N |  | 0 |
| 64 | D-26093063 | 2026-09-28 13:21 | Vantaa | Customs document | Email PDF | Finnish | Y | good | 7 | 6.5 | N |  | 0 |
| 65 | D-26093064 | 2026-09-28 12:35 | Vantaa | POD | Email PDF | Finnish | Y | good | 1 | 3.4 | N |  | 2 |
| 66 | D-26093065 | 2026-10-02 12:14 | Vantaa | Delivery note | Email PDF | Lithuanian | N | good | 1 | 3.1 | N |  | 2 |
| 67 | D-26093066 | 2026-09-29 14:47 | Tampere | POD | Driver app photo | Finnish | Y | good | 1 | 3.1 | N |  | 1 |
| 68 | D-26093067 | 2026-10-02 11:06 | Vantaa | Packing list | Email PDF | Finnish | N | fair | 3 | 3.5 | N |  | 3 |
| 69 | D-26093068 | 2026-10-02 14:05 | Vantaa | POD | Email PDF | Finnish | N | good | 1 | 3.1 | N |  | 0 |
| 70 | D-26093069 | 2026-10-01 08:31 | Vantaa | Delivery note | Paper scan | English | N | good | 4 | 3.5 | N |  | 10 |
| 71 | D-26093070 | 2026-10-01 14:33 | Tampere | POD | Driver app photo | Swedish | Y | good | 1 | 3.9 | N |  | 0 |
| 72 | D-26093071 | 2026-10-02 12:25 | Tampere | Packing list | Paper scan | Swedish | Y | good | 2 | 4.6 | N |  | 8 |
| 73 | D-26093072 | 2026-10-02 14:15 | Vantaa | POD | Paper scan | Finnish | N | fair | 1 | 2.8 | N |  | 5 |
| 74 | D-26093073 | 2026-09-30 14:11 | Vantaa | POD | Driver app photo | Finnish | N | good | 1 | 2.2 | N |  | 1 |
| 75 | D-26093074 | 2026-09-29 10:57 | Vantaa | Packing list | Paper scan | Finnish | N | fair | 4 | 4.6 | N |  | 6 |
| 76 | D-26093075 | 2026-09-29 07:51 | Vantaa | Customs document | Email PDF | Polish | N | good | 2 | 3.3 | N |  | 2 |
| 77 | D-26093076 | 2026-09-28 08:20 | Vantaa | CMR waybill | Email PDF | English | N | good | 1 | 1.9 | N |  | 3 |
| 78 | D-26093077 | 2026-09-30 10:52 | Vantaa | CMR waybill | Paper scan | Finnish | N | poor | 1 | 3.7 | N |  | 5 |
| 79 | D-26093078 | 2026-09-28 12:46 | Tampere | Packing list | Email PDF | English | N | good | 1 | 3.1 | N |  | 1 |
| 80 | D-26093079 | 2026-09-30 13:45 | Tampere | POD | Paper scan | Estonian | Y | good | 1 | 3.7 | N |  | 6 |
| 81 | D-26093080 | 2026-10-01 10:23 | Oulu | CMR waybill | Driver app photo | Polish | N | good | 1 | 2.8 | N |  | 0 |
| 82 | D-26093081 | 2026-10-01 14:47 | Tampere | POD | Email PDF | Finnish | N | good | 1 | 2.7 | N |  | 3 |
| 83 | D-26093082 | 2026-09-30 11:37 | Vantaa | CMR waybill | Email PDF | Lithuanian | N | fair | 1 | 2.5 | N |  | 3 |
| 84 | D-26093083 | 2026-09-28 11:02 | Vantaa | Delivery note | Email PDF | English | N | good | 1 | 2.5 | N |  | 2 |
| 85 | D-26093084 | 2026-10-02 09:43 | Vantaa | POD | Paper scan | Finnish | N | poor | 1 | 3.5 | N |  | 8 |
| 86 | D-26093085 | 2026-10-02 14:37 | Tampere | Delivery note | Driver app photo | Estonian | N | fair | 3 | 3.6 | N |  | 0 |
| 87 | D-26093086 | 2026-09-28 13:44 | Vantaa | CMR waybill | Email PDF | Estonian | N | good | 1 | 3.5 | N |  | 3 |
| 88 | D-26093087 | 2026-09-29 15:52 | Vantaa | CMR waybill | Driver app photo | English | N | good | 1 | 1.8 | N |  | 0 |
| 89 | D-26093088 | 2026-10-01 09:04 | Vantaa | CMR waybill | Driver app photo | Finnish | Y | poor | 1 | 5.2 | N |  | 1 |
| 90 | D-26093089 | 2026-10-01 07:22 | Tampere | Delivery note | Paper scan | English | N | poor | 4 | 5.1 | N |  | 7 |
| 91 | D-26093090 | 2026-09-28 06:23 | Tampere | Delivery note | Driver app photo | English | N | good | 4 | 4 | N |  | 0 |
| 92 | D-26093091 | 2026-09-28 06:32 | Oulu | CMR waybill | Driver app photo | Finnish | N | good | 1 | 2.4 | N |  | 0 |
| 93 | D-26093092 | 2026-09-29 06:45 | Tampere | CMR waybill | Paper scan | Polish | Y | good | 1 | 3.4 | Y | pallet count | 1 |
| 94 | D-26093093 | 2026-10-02 11:28 | Vantaa | POD | Email PDF | Estonian | Y | good | 1 | 3.7 | N |  | 2 |
| 95 | D-26093094 | 2026-09-28 11:52 | Vantaa | Packing list | Paper scan | Finnish | N | good | 2 | 3.2 | N |  | 8 |
| 96 | D-26093095 | 2026-09-29 11:07 | Oulu | Delivery note | Paper scan | Finnish | N | good | 4 | 3.6 | N |  | 4 |
| 97 | D-26093096 | 2026-09-29 11:38 | Tampere | POD | Driver app photo | Finnish | N | good | 1 | 2.5 | N |  | 1 |
| 98 | D-26093097 | 2026-09-28 09:12 | Tampere | Packing list | Paper scan | Finnish | N | good | 3 | 3.3 | N |  | 1 |
| 99 | D-26093098 | 2026-09-29 08:00 | Tampere | CMR waybill | Driver app photo | Finnish | Y | poor | 1 | 4.2 | N |  | 0 |
| 100 | D-26093099 | 2026-10-01 15:06 | Tampere | Delivery note | Paper scan | Swedish | N | good | 2 | 3.8 | N |  | 7 |
| 101 | D-26093100 | 2026-09-29 12:19 | Tampere | POD | Email PDF | Polish | N | fair | 1 | 3.5 | N |  | 2 |
| 102 | D-26093101 | 2026-09-29 09:20 | Vantaa | POD | Paper scan | Swedish | Y | fair | 1 | 4.1 | N |  | 5 |
| 103 | D-26093102 | 2026-10-01 08:52 | Vantaa | POD | Paper scan | Finnish | N | fair | 1 | 2.2 | N |  | 8 |
| 104 | D-26093103 | 2026-09-28 06:49 | Tampere | POD | Email PDF | Finnish | Y | fair | 1 | 4 | N |  | 0 |
| 105 | D-26093104 | 2026-10-02 14:14 | Tampere | CMR waybill | Paper scan | Finnish | N | good | 1 | 2.5 | N |  | 10 |
| 106 | D-26093105 | 2026-09-29 07:49 | Tampere | POD | Driver app photo | Finnish | Y | fair | 1 | 3.4 | N |  | 1 |
| 107 | D-26093106 | 2026-10-02 10:09 | Oulu | CMR waybill | Email PDF | English | Y | good | 1 | 3.7 | Y | remarks not entered | 3 |
| 108 | D-26093107 | 2026-10-01 15:25 | Oulu | POD | Driver app photo | Estonian | N | poor | 1 | 4.8 | N |  | 1 |
| 109 | D-26093108 | 2026-10-02 06:43 | Vantaa | CMR waybill | Driver app photo | Finnish | N | fair | 1 | 2.3 | N |  | 0 |
| 110 | D-26093109 | 2026-09-29 11:22 | Vantaa | Packing list | Driver app photo | English | N | poor | 3 | 5.3 | N |  | 0 |
| 111 | D-26093110 | 2026-10-02 11:39 | Vantaa | POD | Email PDF | Estonian | N | fair | 1 | 2.9 | N |  | 3 |
| 112 | D-26093111 | 2026-09-30 12:46 | Vantaa | Delivery note | Paper scan | English | Y | fair | 3 | 3.7 | N |  | 2 |
| 113 | D-26093112 | 2026-10-02 12:29 | Oulu | POD | Driver app photo | Estonian | N | good | 1 | 3.3 | N |  | 0 |
| 114 | D-26093113 | 2026-09-30 12:09 | Vantaa | CMR waybill | Paper scan | Swedish | Y | good | 1 | 4.3 | N |  | 7 |
| 115 | D-26093114 | 2026-09-28 06:26 | Vantaa | POD | Email PDF | Finnish | Y | good | 1 | 2.9 | N |  | 3 |
| 116 | D-26093115 | 2026-10-02 14:53 | Vantaa | CMR waybill | Driver app photo | Estonian | N | good | 1 | 3.1 | N |  | 0 |
| 117 | D-26093116 | 2026-09-28 12:09 | Vantaa | CMR waybill | Email PDF | Finnish | N | good | 1 | 2.4 | N |  | 3 |
| 118 | D-26093117 | 2026-10-02 12:29 | Vantaa | POD | Driver app photo | English | Y | good | 1 | 3 | N |  | 1 |
| 119 | D-26093118 | 2026-10-01 11:21 | Tampere | POD | Email PDF | Estonian | N | fair | 1 | 2.7 | N |  | 1 |
| 120 | D-26093119 | 2026-10-01 12:13 | Vantaa | CMR waybill | Email PDF | Swedish | N | fair | 1 | 3.6 | N |  | 2 |
| 121 | D-26093120 | 2026-10-01 10:58 | Vantaa | CMR waybill | Driver app photo | Finnish | N | fair | 1 | 3.1 | N |  | 0 |
| 122 | D-26093121 | 2026-10-01 12:26 | Tampere | POD | Paper scan | Estonian | N | good | 1 | 2.9 | N |  | 3 |
| 123 | D-26093122 | 2026-09-28 10:14 | Vantaa | Customs document | Driver app photo | Finnish | N | poor | 6 | 6.1 | Y | pallet count | 0 |
| 124 | D-26093123 | 2026-09-28 06:10 | Tampere | POD | Driver app photo | Finnish | N | fair | 1 | 2.4 | N |  | 1 |
| 125 | D-26093124 | 2026-10-02 08:34 | Vantaa | POD | Paper scan | English | N | good | 1 | 2.3 | N |  | 10 |
| 126 | D-26093125 | 2026-09-30 13:46 | Vantaa | POD | Email PDF | Finnish | N | good | 1 | 3.1 | N |  | 2 |
| 127 | D-26093126 | 2026-09-28 11:51 | Tampere | CMR waybill | Email PDF | Finnish | N | good | 1 | 1.9 | N |  | 0 |
| 128 | D-26093127 | 2026-09-29 12:54 | Tampere | Delivery note | Email PDF | Lithuanian | N | good | 2 | 3.5 | N |  | 3 |
| 129 | D-26093128 | 2026-09-29 09:30 | Tampere | POD | Driver app photo | Finnish | N | poor | 1 | 3.6 | N |  | 0 |
| 130 | D-26093129 | 2026-10-01 15:00 | Vantaa | Delivery note | Paper scan | English | N | fair | 3 | 3.3 | N |  | 5 |
| 131 | D-26093130 | 2026-10-02 07:26 | Oulu | POD | Email PDF | Finnish | Y | good | 1 | 3.2 | N |  | 2 |
| 132 | D-26093131 | 2026-10-01 09:10 | Tampere | POD | Email PDF | Finnish | N | good | 1 | 2.3 | N |  | 3 |
| 133 | D-26093132 | 2026-10-02 06:54 | Vantaa | CMR waybill | Paper scan | Polish | Y | good | 1 | 3.7 | N |  | 8 |
| 134 | D-26093133 | 2026-10-01 14:20 | Oulu | Customs document | Driver app photo | Finnish | N | fair | 6 | 5 | N |  | 1 |
| 135 | D-26093134 | 2026-10-01 15:22 | Vantaa | CMR waybill | Paper scan | Finnish | Y | good | 1 | 3 | N |  | 10 |
| 136 | D-26093135 | 2026-10-02 09:43 | Vantaa | CMR waybill | Email PDF | Finnish | N | good | 1 | 2.9 | N |  | 3 |
| 137 | D-26093136 | 2026-10-01 08:00 | Oulu | POD | Paper scan | Swedish | Y | poor | 1 | 5.1 | N |  | 2 |
| 138 | D-26093137 | 2026-09-29 09:31 | Tampere | POD | Paper scan | English | N | fair | 1 | 2.7 | N |  | 3 |
| 139 | D-26093138 | 2026-09-29 13:01 | Tampere | CMR waybill | Driver app photo | English | Y | poor | 1 | 4.2 | N |  | 0 |
| 140 | D-26093139 | 2026-10-01 08:25 | Oulu | Customs document | Paper scan | Finnish | N | good | 6 | 4.8 | N |  | 7 |
| 141 | D-26093140 | 2026-09-30 13:45 | Vantaa | POD | Driver app photo | Finnish | N | poor | 1 | 3.1 | N |  | 1 |
| 142 | D-26093141 | 2026-09-28 15:07 | Oulu | POD | Email PDF | Swedish | N | good | 1 | 3.1 | N |  | 2 |
| 143 | D-26093142 | 2026-09-30 06:49 | Vantaa | Customs document | Paper scan | Finnish | N | good | 5 | 4.6 | N |  | 8 |
| 144 | D-26093143 | 2026-09-29 08:15 | Vantaa | CMR waybill | Paper scan | Finnish | N | good | 1 | 2.4 | N |  | 7 |
| 145 | D-26093144 | 2026-09-28 12:45 | Oulu | POD | Paper scan | Estonian | Y | good | 1 | 3.4 | N |  | 3 |
| 146 | D-26093145 | 2026-10-02 13:35 | Tampere | Delivery note | Paper scan | Finnish | N | good | 2 | 3 | N |  | 4 |
| 147 | D-26093146 | 2026-09-28 11:20 | Vantaa | Delivery note | Paper scan | Lithuanian | N | good | 1 | 2.8 | N |  | 2 |
| 148 | D-26093147 | 2026-10-02 08:48 | Vantaa | POD | Email PDF | Estonian | N | good | 1 | 3.4 | N |  | 0 |
| 149 | D-26093148 | 2026-10-02 12:33 | Vantaa | Delivery note | Driver app photo | Finnish | N | fair | 2 | 2.4 | N |  | 0 |
| 150 | D-26093149 | 2026-09-28 11:08 | Vantaa | CMR waybill | Paper scan | Finnish | N | good | 1 | 2.6 | N |  | 5 |
| 151 | D-26093150 | 2026-09-28 10:06 | Vantaa | CMR waybill | Email PDF | Finnish | N | good | 1 | 2.9 | N |  | 3 |

## Sheet: CS_Email_Tally

| Row | tally_month | category | emails_in_tally_week | avg_response_hours | answerable_from_TMS_data | contains_consumer_personal_data |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | 2026-04 | Track & trace | 827 | 6 | Y | Y |
| 3 | 2026-04 | Booking change | 247 | 7.6 | Y | N |
| 4 | 2026-04 | Delivery time request | 212 | 7.4 | Y | Y |
| 5 | 2026-04 | Damage / claim | 130 | 7.1 | N | Y |
| 6 | 2026-04 | Invoicing question | 160 | 5.1 | N | N |
| 7 | 2026-04 | Quote request | 91 | 6.7 | N | N |
| 8 | 2026-04 | Other | 115 | 6.7 | N | N |
| 9 | 2026-05 | Track & trace | 787 | 4.1 | Y | Y |
| 10 | 2026-05 | Booking change | 247 | 4 | Y | N |
| 11 | 2026-05 | Delivery time request | 186 | 7.2 | Y | Y |
| 12 | 2026-05 | Damage / claim | 148 | 6.5 | N | Y |
| 13 | 2026-05 | Invoicing question | 166 | 5.6 | N | N |
| 14 | 2026-05 | Quote request | 96 | 4.1 | N | N |
| 15 | 2026-05 | Other | 112 | 6.4 | N | N |
| 16 | 2026-06 | Track & trace | 763 | 4.7 | Y | Y |
| 17 | 2026-06 | Booking change | 238 | 4.3 | Y | N |
| 18 | 2026-06 | Delivery time request | 198 | 5.6 | Y | Y |
| 19 | 2026-06 | Damage / claim | 133 | 6 | N | Y |
| 20 | 2026-06 | Invoicing question | 163 | 6.2 | N | N |
| 21 | 2026-06 | Quote request | 77 | 6.3 | N | N |
| 22 | 2026-06 | Other | 106 | 6.9 | N | N |
| 23 | 2026-07 | Track & trace | 638 | 3.5 | Y | Y |
| 24 | 2026-07 | Booking change | 205 | 4.9 | Y | N |
| 25 | 2026-07 | Delivery time request | 167 | 4.4 | Y | Y |
| 26 | 2026-07 | Damage / claim | 124 | 5.9 | N | Y |
| 27 | 2026-07 | Invoicing question | 123 | 5.8 | N | N |
| 28 | 2026-07 | Quote request | 77 | 3.8 | N | N |
| 29 | 2026-07 | Other | 97 | 5.1 | N | N |
| 30 | 2026-08 | Track & trace | 908 | 7.3 | Y | Y |
| 31 | 2026-08 | Booking change | 239 | 4.6 | Y | N |
| 32 | 2026-08 | Delivery time request | 212 | 5.2 | Y | Y |
| 33 | 2026-08 | Damage / claim | 157 | 7.5 | N | Y |
| 34 | 2026-08 | Invoicing question | 149 | 7.7 | N | N |
| 35 | 2026-08 | Quote request | 87 | 4.3 | N | N |
| 36 | 2026-08 | Other | 114 | 6.6 | N | N |
| 37 | 2026-09 | Track & trace | 836 | 6.4 | Y | Y |
| 38 | 2026-09 | Booking change | 264 | 6.6 | Y | N |
| 39 | 2026-09 | Delivery time request | 216 | 6 | Y | Y |
| 40 | 2026-09 | Damage / claim | 147 | 4.7 | N | Y |
| 41 | 2026-09 | Invoicing question | 177 | 7.7 | N | N |
| 42 | 2026-09 | Quote request | 91 | 6.6 | N | N |
| 43 | 2026-09 | Other | 106 | 8.3 | N | N |

## Sheet: Data_Inventory

| Row | system | dataset | data_since | volume | format | access_method | data_owner | known_quality_issues |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | WMS | Receipts, putaways, picks, shipments, inventory movements | 2020-01 | approx. 48 M transaction rows | SQL Server tables | Read-only SQL (IT Manager) | Operations Director | Pre-2020 data in old structure; pallet types inconsistent |
| 3 | RouteLine TMS | Transport orders, shipments, POD status, freight costs | 2018-03 | approx. 1.4 M shipments | Cloud database | REST API, single records; bulk export as paid service | Operations Director | Customer IDs differ from Business Central |
| 4 | RouteLine TMS | Document log (registered freight documents) | 2019-06 | approx. 1.5 M entries | Cloud database | Report export (CSV), max 100,000 rows | Operations Director | Registration date = scan date for paper documents |
| 5 | Document archive | Scanned freight documents | 2019-06 | approx. 1.5 M PDF files, 2.3 TB | PDF (image only, no text layer) | File share | No owner | No index; file names inconsistent; mixed quality |
| 6 | Driver app | POD photos and signatures | 2020-05 | approx. 400 k images | JPG in TMS | Via TMS | Operations Director | Night photos, blur, partial documents |
| 7 | Business Central | Invoices, credit notes, customers | 2022-01 | approx. 95 k invoices | Cloud ERP | API / OData | CFO | Credit note reasons as free text |
| 8 | Outlook shared mailbox | Customer service emails | 2021-01 | approx. 300 k emails | Exchange Online | Microsoft Graph | Customer Service Team Lead | Personal data of consumers; no categories stored |
| 9 | Telematics | Vehicle position, fuel, driving events | 2019-09 | approx. 120 M position points | Vendor cloud | CSV export | Fleet manager | Not linked to shipments |
| 10 | Customer forecasts | Weekly volume forecasts from customers | 2022 | approx. 12 customers, irregular | Excel attachments in email | Manual | Site managers | Different formats per customer; often missing |
| 11 | Payroll / HR | Working hours, overtime, agency invoices | 2021-01 | approx. 250 k time entries | Payroll system | Excel export | HR manager | Contains employee personal data |

## Sheet: Use_Case_Scoring

| Row | use_case | business_value | data_availability | technical_feasibility | compliance_risk_low_is_risky | management_priority | comment |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | Freight document processing (extraction to TMS/ERP) | 5 | 4 | 4 | 3 | 1 | Clear baseline: clerk hours, error rate, POD delay |
| 3 | Warehouse labour demand forecasting | 4 | 3 | 2 | 3 | 2 | Depends on WMS data quality and customer forecasts |
| 4 | Customer service email triage and reply drafting | 4 | 4 | 3 | 2 | 3 | Personal data - needs AI policy and DPA review |
| 5 | Route optimisation with real unloading times | 3 | 2 | 2 | 3 | 4 | TMS vendor update expected 2027 |
| 6 | Predictive maintenance (trucks, forklifts) | 2 | 3 | 3 | 4 | 5 | Telematics data exists; fleet manager not yet involved |
| 7 | Automatic customs declarations | 3 | 2 | 1 | 1 | Not now | Regulatory and liability risk considered too high |