Contents:
enfr_english  enfr_french  en_jameng_tgt.txt  fr_jamfra_tgt.txt  jm_jameng_src.txt  jm_jamfra_src.txt

Jamaican-English bitext:
	jm_jameng_src.txt and en_jameng_tgt.txt

Jamaican-French bitext:
	jm_jamfra_src.txt and fr_jamfra_tgt.txt

English-French bitext (used for augmentation):
	enfr_english and enfr_french

When using transfer learning from English, we translate from English and Jamaican to French, using the Jamaican-French and English-French bitexts. In this case, Jamaican is the LRL (low-resource language), English is the HRL (high-resource language used for transfer learning), and French is the TGT (target language for both).

This is different from our other experiments, where English is always the TGT. We use English as HRL instead here since it has a close relation to Jamaican. We should make a note of this in our study.
