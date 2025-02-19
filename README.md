# CR-GSL
This project provides a description of the data used in the article ‘Anomaly recognition method for cigarette-rolling process based on graph structure learning’ and showcases a small portion of the data utilized in the article.

The data corresponds to Table 2 in Section 4.1 of the article. This multivariate time series includes 27 indicators for 10,000 cigarettes. During the production process, 27 indicators were collected for each cigarette, covering three steps: VE, SE, and MAX.
#
| No.       | Indicator Name                       | No. | Indicator Name                    |
| --------- | ------------------------------------ | --- | --------------------------------- |
| 1         | Suction tape tension pressure        | 15  | Weight of cigarette in sections 4 |
| 2         | Suction rod conveyor vacuum pressure | 16  | Weight of cigarette in sections 5 |
| 3         | Pressure of primary separator        | 17  | Tobacco temperature               |
| 4         | Suction tape Initial position        | 18  | Speed of machine operation        |
| 5         | Suction tape position                | 19  | MAX gas source pressure           |
| 6         | SE belt tension                      | 20  | MAX large fan pressure            |
| 7         | SE gas source pressure               | 21  | Rolling plate temperature         |
| 8         | Sealer temperature                   | 22  | Ignition end density              |
| 9         | Spider hand small fan pressure       | 23  | Cigarette OTIS                    |
| 10        | Cigarette bar total weight           | 24  | Cap gas source pressure average   |
| 11        | Position of compaction end           | 25  | Draw resistance                   |
| 12        | Weight of cigarette in sections 1    | 26  | Ventilating strength              |
| 13        | Weight of cigarette in sections 2    | 27  | Air leakage                       |
| 14        | Weight of cigarette in sections 3    |     |				
#





The implementation of the CR-GSL is conducted on a computer equipped with a Microsoft Windows 10 operating system, an Intel(R) Xeon(R) Gold 6226R CPU, 128GB RAM, and a GPU of NVIDIA GeForce RTX 3080. The software-related is Python 3.6, cuda 10.2, Pytorch 1.5.1.


Since the data was initially processed using MATLAB, only '.mat' files are provided here for reference. If specific data in CSV format is required, please contact the authors to obtain it.


If you have additional questions regarding the data or the article, please contact clsnnqns@163.com.
