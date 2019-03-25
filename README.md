# debugtools

Debug tools for Cookbook demo


To run the debug translation process do the following

sourceanalyzer -b <Your Fortify SCA Build ID> -no-default-rules -rules debugTranslationRule.xml -scan -f debugtranslationScan.fpr


reportgenerator -source debugtranslationScan.fpr -format rtf -f debugtranslationScan.rtf -template DebugTranslationReport.xml


Open RTF file in wordpad or Word and review.
