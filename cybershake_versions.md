# Summary of Cybershake NZ Executions Across All Versions

## Table Notes
1. **Source Types**  
   - (SC): Shallow Crustal  
   - (V): Volcanic  
   - (Sub): Subduction  

2. **Topography Types**  
   - (B): Bulldozed  
   - (SQT): Squashed–Tapered  

3. **HPC Providers**  
   - (NeSI): New Zealand eScience Infrastructure  
   - (KISTI): Korea Institute of Science and Technology Information  
   - (ESNZ): Earth Science New Zealand  

4. Prototype shallow-crustal implementation.  
5. First 100 m-resolution simulations, focused on smaller-magnitude faults in the upper South Island and lower North Island.  
6. Extended from v20.6, with additional realizations added to correct the statistical distribution of hypocenter locations.  
7. Extended from v20.9, with additional realizations added to correct the statistical distribution of hypocenter locations.  
8. An aggregate compilation of simulations from v20.6, v20.9, v24.8, and v24.9.  
9. Selective reruns of a subset of simulations from v21.1, v22.11, v22.12, and v23.1 for consistency.  

---

## Executions Table

| Ver.   | Date     | No. Sources | Source Type | Region            | NZVM Ver. | Topo. | Vs30 | SRF Ver. | Spatial Disc. | Trans. Freq. | Temp. Disc. | HPC   | Core-Hours | Remarks |
|--------|----------|-------------|-------------|-------------------|-----------|-------|------|----------|---------------|--------------|-------------|-------|------------|---------|
| v17.9  | Aug-2017 | 110         | SC, V       | South Island NZ   | 1.65      | B     | 17.0 | 3.3      | 400m          | 0.25Hz       | 0.025s      | NeSI  | 0.03M      | See Note 4 |
| v18.6  | Jun-2018 | 483         | SC, V       | Whole NZ          | 1.65      | B     | 18.0 | 3.3      | 400m          | 0.25Hz       | 0.025s      | NeSI  | 0.3M       | -- |
| v19.5  | May-2019 | 471         | SC, V       | Whole NZ          | 2.02      | B     | 19.0 | 3.3      | 400m          | 0.25Hz       | 0.025s      | NeSI  | 0.3M       | -- |
| v20.4  | Apr-2020 | 478         | SC, V       | Whole NZ          | 2.03      | B     | 19.0 | 5.4.2    | 400m          | 0.25Hz       | 0.005s      | NeSI  | 0.3M       | -- |
| v20.5  | May-2020 | 8           | Sub         | Whole NZ          | 2.03      | B     | 19.0 | 5.4.2    | 400m          | 0.25Hz       | 0.005s      | NeSI  | 0.1M       | -- |
| v20.6  | Jun-2020 | 478         | SC, V       | Whole NZ          | 2.03      | B     | 20.3 | 5.4.2    | 200m          | 0.5Hz        | 0.005s      | NeSI  | 3.4M       | -- |
| v20.9  | Sep-2020 | 8           | Sub         | Whole NZ          | 2.03      | B     | 20.3 | 5.4.2    | 200m          | 0.5Hz        | 0.005s      | NeSI  | 1M         | -- |
| v21.1  | Jun-2021 | 21          | SC          | South Island NZ   | 2.06      | SQT   | 20.3 | 5.4.2    | 100m          | 1Hz          | 0.005s      | KISTI | 5.5M       | See Note 5 |
| v21.6  | Jun-2021 | 22          | SC          | South Island NZ   | 2.06      | B     | 20.3 | 5.4.2    | 100m          | 1Hz          | 0.005s      | NeSI  | 2.3M       | -- |
| v21.6x | Jun-2021 | 60          | SC          | South Island NZ   | 2.06      | B     | 20.3 | 5.4.2    | 100m          | 1Hz          | 0.005s      | KISTI | 5.5M       | -- |
| v22.2  | Feb-2022 | 5           | SC          | South Island NZ   | 2.06      | B     | 20.3 | 5.4.2    | 100m          | 1Hz          | 0.005s      | NeSI  | 1M         | -- |
| v22.4  | Apr-2022 | 34          | SC          | South Island NZ   | 2.06      | B     | 20.3 | 5.4.2    | 100m          | 1Hz          | 0.005s      | KISTI | 13M        | -- |
| v22.11 | Nov-2022 | 4           | SC          | Wellington Region | 2.06      | SQT   | 20.3 | 5.4.2    | 100m          | 1Hz          | 0.005s      | NeSI  | 1M         | -- |
| v22.12 | Dec-2022 | 4           | SC          | Wellington Region | 2.06      | SQT   | 20.3 | 5.4.2    | 100m          | 1Hz          | 0.005s      | NeSI  | 1M         | -- |
| v23.5  | Jun-2023 | 19          | SC          | South Island NZ   | 2.06      | B     | 20.3 | 5.4.2    | 100m          | 1Hz          | 0.005s      | KISTI | 3M         | -- |
| v23.7  | Oct-2023 | 18          | SC          | Marlborough Reg.  | 2.06      | B     | 20.3 | 5.4.2    | 100m          | 1Hz          | 0.005s      | KISTI | 3.5M       | -- |
| v23.10 | Oct-2023 | 3           | SC          | South Island NZ   | 2.06      | SQT   | 20.3 | 5.4.2    | 100m          | 1Hz          | 0.005s      | NeSI  | 1M         | -- |
| v24.8  | Nov-2024 | 478         | SC, V       | Whole NZ          | 2.03      | B     | 20.3 | 5.4.2    | 200m          | 0.5Hz        | 0.005s      | NeSI  | 0.7M       | See Note 6 |
| v24.9  | Nov-2024 | 8           | Sub         | Whole NZ          | 2.03      | B     | 20.3 | 5.4.2    | 200m          | 0.5Hz        | 0.005s      | NeSI  | 0.6M       | See Note 7 |
| v25.6  | Jun-2025 | 486         | SC, Sub, V  | Whole NZ          | 2.03      | B     | 20.3 | 5.4.2    | 200m          | 0.5Hz        | 0.005s      | NeSI  | 4.7M       | See Note 8 |
| v25.11 | Nov-2025 | 21          | SC, Sub     | South Island NZ   | 2.06      | B     | 20.3 | 5.4.2    | 100m          | 1Hz          | 0.005s      | NeSI  | --         | See Note 9 |
| v25.12 | Dec-202
