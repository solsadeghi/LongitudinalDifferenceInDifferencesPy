
# Introduction 
It's critical to know if the work we are doing is helping the team reach its organizational goals. The problem is that there are potentially many other effects at play. One analysis method for doing this is called a difference in differences analysis. If I had done nothing, then what would have happened to the numbers I care about or "key performance indicators" (KPI) after people started using my product. If you're looking to measure impact on some quantitative KPIs and you don't have the infrastructure for experiments/"randomized control trials"/"AB Testing", then this type of analysis is for you.

Thanks to Sol Sadeghi (Cosine Data Science team @ Microsoft) for informing me about this analysis technique and helping with the initial code review!

# Demo

To see a full demonstration of the tool with some example data, 
1. Navigate to the `example` directory.
2. Run the following command:
```python
python exampleDIDAnalysis.py
```

# Case Study

Example of how this tool was used inside of Microsoft to show the (5+%) impact of a product on developer productivity within the Windows dision coming soon.

# Getting Started
[Our documentation is available on this repository's wiki.](https://github.com/microsoft/LongitudinalDifferenceInDifferencesPy/wiki)


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
