# anderson-cancer-center

The following data is from the M.D. Anderson Cancer Center, and contains 191 patients diagnosed with Acute Myelogenous Leukaemia, a kind of cancer. Measurements include clinical variables including demographics, history of cancer, chemotherapy or radiation treatments, blood tests, as well as cytogenic, genomic and proteomic measurements. These patients were treated with a particular treatment, and we need to model why some patients responded to the treatment and others did not. A full list of measurements and descriptions are available here, though for this problem, you will not need a crash course in biology. The dataset is available here, and has been downloaded from here.

The task is to model the following targets:

    resp.simple: Response to treatment, categorical (CR: complete response or RESISTANT)
    Relapse: Whether the patient had a relapse, categorical (Yes, No, NA)
    vital status: Final status of patient at the end of study, categorical (A: alive or D: deceased)
    Overall_Survival: Overall survival in weeks from diagnosis to exiting the study, real valued data
    Remission Duration: Duration of time in remission in weeks (numerical data or NA)

Build linear regression based models that predict each of the above targets. Note that you have a lot of features (about 271), but only 191 patients, typical of most medical applications. You cannot use vanilla linear regression. This statement is deliberately left open ended. Work with me to come up with a plan to develop and implement your approch in tackling this task, and subsequently write up a report about your efforts. In any report you write, please be sure to cite the paper

Hu et. al., A quantitative analysis of heterogeneities and hallmarks in acute myelogenous leukaemia. Nature Biomedical Engineering, vol 3, Nov 2019, pages 889-901.

for the data.
