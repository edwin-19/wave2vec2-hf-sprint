# Wave2Vec2 Sprint HuggingFace
Huggingfaces released a model for facebooks fairseqs Wave2Vec2 for low resource speech recognition(sound 2 text). The following was my attempt to finetune and train on the malay language and there are several other [repositories](https://github.com/huseinzol05/malaya-speech) doing this but i thought why not try and fine tune for the sprint.

The langauge i was attempting is in bahasa malaysia (Malay).
The other is a special form of english here in Malaysia (Manglish).
So far the attempted finetuning method is Malay. Will attempt to gather more data on manglish

# Notes
- (30/3/2021) : Training Failed, Need to debug
- (30/3/2021: 4:00pm) : Fix logging step and added evaluation step, change new data inputs and fix data gathering methods

# Results
- (30/3/2021): Word Error Rate is 1 (need to debug reasons for high error rate)

# ToDO
- [x] Gather Data
- [x] EDA
- [x] Preprocesing
- [x] Train Wave2Vec2 model
- [x] Inference Script
- [x] Evaluate model
- [ ] Upload model to huggingface hub