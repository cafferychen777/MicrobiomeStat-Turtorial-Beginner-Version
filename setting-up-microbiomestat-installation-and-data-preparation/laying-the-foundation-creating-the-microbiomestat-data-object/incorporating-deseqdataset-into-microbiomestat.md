---
description: Learn the methodology to import DESeqDataSet data into MicrobiomeStat.
---

# Incorporating DESeqDataSet into MicrobiomeStat 🎯🔍

Find the bulls-eye of your microbiome research by focusing your **DESeqDataSet** into the **MicrobiomeStat** lens! 🎯🔍

```r
# 📚 Example Code (replace with your real dataset!)
# Load necessary packages
 library(airway)
 library(DESeq2)

# Load dataset
 data("airway")
 dds <- DESeqDataSet(airway, design = ~ cell + dex)

# 🔎 Convert DESeqDataSet to MicrobiomeStat data object
 data.obj <- mStat_convert_DESeqDataSet_to_data_obj(dds)
```

The `mStat_convert_DESeqDataSet_to_data_obj` function helps you get a clear view of your DESeqDataSet by converting it into a **MicrobiomeStat data object**. Here's what you need:

* **dds.obj**: Your DESeqDataSet object to be transformed. 🔬

The function crafts a **MicrobiomeStat data object** with care, containing:

* **feature.tab**: A matrix 🟦 with your counts data.
* **meta.dat**: A data frame 📋 with your sample data.
* **feature.ann**: A matrix 🟦 with feature annotations.

Remember, clarity is key in research! This function ensures only features with a sum > 0 from your counts data are retained in the output. So, you can focus 🧐 on what truly matters!

With `mStat_convert_DESeqDataSet_to_data_obj`, you are ready to bring your DESeqDataSet into the fold of MicrobiomeStat's powerful tools. Get set and zoom into your exploration now! 🔬🚀
