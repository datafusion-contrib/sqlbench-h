# SQLBench-H

## Overview

SQLBench-H is a SQL benchmark derived from [TPC-H](https://www.tpc.org/tpch/) under the terms of the Transaction
Processing Council's [Fair Use Policy](https://www.tpc.org/tpc_documents_current_versions/pdf/tpc_fair_use_quick_reference_v1.0.0.pdf).

This benchmark is limited to measuring the execution time of individual queries derived from TPC-H and is intended for
use as a way to compare performance between open source query engines.

## How does this differ from TPC-H

- This benchmark only measures execution times for individual queries
- Only Parquet input files are supported
- Non-SQL solutions are allowed (such as DataFrame-based solutions)

## Legal Stuff

SQLBench-H is a Non-TPC Benchmark. Any comparison between official TPC Results with non-TPC workloaH is prohibited by
the TPC.

TPC-H is Copyright &copy; 1993-2022 Transaction Processing Performance Council. The full TPC-H specification in PDF
format can be found [here](https://www.tpc.org/TPC_Documents_Current_Versions/pdf/TPC-H_v3.0.1.pdf)

TPC, TPC Benchmark and TPC-H are trademarks of the Transaction Processing Performance Council.