## Hi, I'm Cameron

I'm a data and ML engineer in San Diego. I turn messy public data like aerial imagery, parcel records, permits, lidar, and smart-meter readings into pipelines people can make decisions with. B.S. in Applied Mathematics with Highest Honors, UC Santa Cruz, 2026.

Open to data engineering, ML, and data science roles in San Diego, Los Angeles, and San Francisco, in person, hybrid, or remote.

### Projects

**[solar-soiling-detection](https://github.com/CameronGordonn/solar-soiling-detection)** · Engineering Lead, Better Behavior Foundation · [dashboard](https://betterbehaviorfoundation.com/tools/dashboard)
- Pipeline joining 21 cm county aerial imagery, parcel records, building permits, and lidar that mapped 3,362 rooftop solar arrays at 1,865 sites in Santa Cruz County.
- RF-DETR + SAM2 detector retrained on 976 labeled image chips scores 0.826 F1 on a held-out town and raised recall against unseen building permits from 10% to 74%.
- Metered data from 149 rooftops showed routine panel cleaning loses money for the average home: one wash recovers a median $28 against a $150 service call.

**[energy-advisor](https://github.com/CameronGordonn/energy-advisor)** · [try it](https://camerongordonn.github.io/energy-advisor/)
- Reproduces a California household's real utility bills from its own meter data (11 of 11 PG&E bills within $2), then ranks every rate plan it qualifies for.
- Runs in the browser on Pyodide, so your data never leaves your computer.

**[sparse-scan-SEM-reconstruction](https://github.com/CameronGordonn/sparse-scan-SEM-reconstruction)** · [try it](https://camerongordonn.github.io/sparse-scan-SEM-reconstruction/)
- Fills in the pixels a fast electron-microscope scan skips. A U-Net beat the traditional methods in all 30 simulated conditions by about 2 dB at 0.03 s per image.
- A diffusion model matched the U-Net but cost about 600x the compute.

**[jobradar](https://github.com/CameronGordonn/jobradar)**
- Finds jobs on USAJOBS and company boards the big sites miss, then reranks them against a written rubric with the Claude API. Runs every morning on a schedule.

Also at BBF: built booking flows and the Prolific payout system for a 1,413-person real-money A/B test that doubled airline donation rates, from 18% to 42%.

### Contact

[LinkedIn](https://www.linkedin.com/in/cameron-gordon-3243662b8)
