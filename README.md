# cuffless-blood-pressure-estimation-using-VitalDB-databank
This repository is developed for cuffless blood pressure estimation using VitalDB database. This includes data downloading, feature extraction and processing.

The [VitalDB databank](https://vitaldb.net/dataset/?query=overview&documentId=13qqajnNZzkN7NZ9aXnaQ-47NWy7kx-a6gbrcEsi-gak&sectionId=h.1fo5zknztqnw) was obtained from non-cardiac (general, thoracic, urologic, and gynaecologic) surgery patients who underwent routine or emergency surgery in 10 out of 31 operating rooms of **Seoul National University Hospital, Seoul, Republic of Korea**. The dataset consists of a total of **557,622 data tracks from 6,388 cases**.

There are several different devices used to collect different parameters from patients, some are in waveforms and some are in numeric forms. As I focus on continuous blood pressure estimation, so electrocardiogram (ECG), photoplethysmogram (PPG) and blood pressure (BP) waveforms are required. There is one device that collects these three waveforms as shown below. 
