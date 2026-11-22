FODS Programs 21–40: executed Colab notebooks

Contents
- Program_21.ipynb through Program_40.ipynb
- Each notebook contains executed outputs generated locally from the supplied CSVs or from the original Word document's deterministic/built-in data logic.
- Interactive prompts were replaced with clearly labeled sample values where needed.

Data files
- Programs 21–28 use the supplied Q21–Q28 CSV files.
- Programs 29–30 use the supplied Q29 and Q30 CSV files; the original Random Forest metrics and CART regression workflows are retained.
- Programs 31–39 use the supplied Q31–Q39 CSV files.
- Program 40 needs no CSV: the Word source generates its own 500-player sample, which was used as written.

Open in Google Colab
1. Download and unzip this package.
2. In Colab, choose File → Upload notebook and select a Program_N.ipynb.
3. Choose Runtime → Run all.
4. If the notebook asks for a CSV, upload the matching file named in its DATA_FILE variable. Programs 29 and 30 also ask for their corresponding CSV when it is not already in the runtime.

The notebooks already show the real outputs from this run. Running them again in Colab will recompute outputs using the uploaded data and the labeled sample values.
