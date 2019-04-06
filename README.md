# RGB-T fusion tracking：papers，results & datasets
The papers and results about RGB-T fusion tracking

## Papers
### Journal papers
- Sulan Zhai, Pengpeng Shao, Xinyan Liang, Xin Wang.  
	"Fast RGB-T Tracking via Cross-Modal Correlation Filters." Neurocomputing (2019).[[paper][1]]
- Xiangyuan Lan, Mang Ye, Rui Shao, Bineng Zhong, Pong C.Yuen, Huiyu Zhou.  
	  "Learning Modality-Consistency Feature Templates: A Robust RGB-Infrared Tracking System."IEEE TRANSACTIONS ON INDUSTRIAL ELECTRONICS (2019).[[paper][2]]
- Chenglong Li, Chengli Zhu, Jian Zhang, Bin Luo, Xiaohao Wu, and Jin Tang. 
	  "Learning Local-Global Multi-Graph Descriptors for RGB-T Object Tracking". IEEE Transactions on Circuits and Systems for Video Technology (T-CSVT), (2019).[[paper][3]] (**FPS: 0.7**)
- Xiangyuan Lan, Mang Ye, Shengping Zhang, Huiyu Zhou, Pong C. Yuen.
	  "Modality-correlation-aware sparse representation for RGB-infrared object tracking".Pattern Recognition Letters, 2019
- Chenglong Li, Xiaohao Wu, Nan Zhao, Xiaochun Cao, and Jin Tang. 
	  "Fusing Two-Stream Convolutional Neural Networks for RGB-T Object Tracking". Neurocomputing (NEUCOM), 281: 78-85, 2018.[[paper][4]]
- Chenglong Li, Chengli Zhu, Shaofei Zheng, Bin Luo, and Jin Tang. 
	  "Two-Stage Modality-Graphs Regularized Manifold Ranking for RGB-T Tracking". Signal Processing: Image Communication (SPIC), 68: 207-217, 2018. [[paper][5]]
- Chenglong Li, Xiang Sun, Xiao Wang, Lei Zhang, and Jin Tang. 
	  "Grayscale-thermal Object Tracking via Multi-task Laplacian Sparse Representation". IEEE Transactions on Systems, Man, and Cybernetics: Systems (T-SMCS), 47(4): 673-681, 2017.[[paper][6]]

### Conference papers
- Xingming Zhang, Xuehan Zhang, Xuedan Du, Xiangming Zhou, Jun Yin. 
	 "Learning Multi-domain Convolutional Network for RGB-T Visual Tracking." CISP-BMEI 2018.
- Chenglong Li, Chengli Zhu, Yan Huang, Jin Tang, Liang Wang.
	   "Cross-Modal Ranking with Soft Consistency and Noisy Labels for Robust RGB-T Tracking." ECCV 2018.  
- Xiangyuan Lan, Mang Ye, Shengping Zhang, Pong C. Yuen. 
	   "Robust Collaborative Discriminative Learning for RGB-Infrared Tracking". AAAI 2018.
- Yulong Wang, Chenglong Li, and Jin Tang.
	“Learning Soft-Consistent Correlation Filters for RGB-T Object Tracking”. PRCV 2018.
- Ningwen Xu, Gang Xiao, Xingchen Zhang, Durga Prasad Bavirisetti.
	"Relative Object Tracking Algorithm Based on Convolutional Neural Network for Visible and Infrared Video Sequences". 4th International Conference on Virtual Reality, 2018
- Chenglong Li, Nan Zhao, Yijuan Lu, Chengli Zhu, and Jin Tang. 
	   "Weighted Sparse Representation Regularized Graph Learning for RGB-T Object Tracking". ACM International Conference on Multimedia (ACM MM), 2017.
- Chenglong Li, Shiyi Hu, Sihan Gao, and Jin Tang. 
	   "Real-time Grayscale-thermal Tracking  via Laplacian Sparse Representation". International Conference on Multimedia Modelling (MMM), Miami, 2016.
	 
### ArXiv
- Chenglong Li, Xinyan Liang, Yijuan Lu, Nan Zhao, and Jin Tang.
	“RGB-T Object Tracking:Benchmark and Baseline”, 2018
- Yabin Zhu, Chenglong Li, Yijuan Lu, Liang Lin, Bin Luo, Jin Tang.
	“FANet : Quality-Aware Feature Aggregation Network for RGB-T Tracking”, 2018

## Datasets and benchmark
- GTOT
	- Paper: Chenglong Li, Hui Cheng, Shiyi Hu, Xiaobai Liu, Jin Tang, Liang Lin.
		“Learning Collaborative Sparse Representation for Grayscale-Thermal Tracking”,  IEEE Transactions on Image Processing (T-IP), 25(12): 5743-5756, 2016. [[paper][7]]
	- Download Link [[Google drive][8]] [[Baidu Cloud][9]]
	- Papers using this dataset
		- Yabin Zhu, Chenglong Li, Yijuan Lu, Liang Lin, Bin Luo, Jin Tang.
		“FANet : Quality-Aware Feature Aggregation Network for RGB-T Tracking”, 2018 (**PR/SR: 88.5/69.8**)
		- Chenglong Li, Xiaohao Wu, Nan Zhao, Xiaochun Cao, and Jin Tang.
			  "Fusing Two-Stream Convolutional Neural Networks for RGB-T Object Tracking". Neurocomputing (NEUCOM), 281: 78-85, 2018.[[paper][10]] (**PR/SR:85.2/62.6. Threshold is 5 pixels**)
		- Yulong Wang, Chenglong Li, and Jin Tang.
			“Learning Soft-Consistent Correlation Filters for RGB-T Object Tracking”. PRCV 2018.(**PR/SR: 85/68.1**)
		- Sulan Zhai, Pengpeng Shao, Xinyan Liang, Xin Wang.  
	   "Fast RGB-T Tracking via Cross-Modal Correlation Filters." Neurocomputing (2019).[[paper][11]] (**PR/SR:77/63.2**)
- RGBT210
	- Paper: Chenglong Li, Nan Zhao, Yijuan Lu, Chenglin  Zhu, Jin Tang.
		“Weighted Sparse Representation Regularized Graph Learning for RGB-T Object Tracking”, ACM International Conference on Multimedia (ACM MM), 2017. [[paper][12]]
	- Download Link [[Google drive][13]][[Baidu Cloud][14]]
	- Papers using this dataset
		- Xingchen Zhang, Gang Xiao, Ping Ye, Dan Qiao, Shengyun Peng.
		  "SiamFT: A Feature-level Fusion Tracking Method Using Fully Convolutional Siamese Networks Based on Visible and Infrared Sequences". ICCV 2019 (submitted).(**PR/SR:65.0/44.3**)
		-  Sulan Zhai, Pengpeng Shao, Xinyan Liang, Xin Wang.  
			   "Fast RGB-T Tracking via Cross-Modal Correlation Filters." Neurocomputing (2019).[[paper][15]] (**PR/SR:52.9/36.3**)
	- Results
- RGBT234
	- Paper: Chenglong Li, Xinyan Liang, Yijuan Lu, Nan Zhao, and Jin Tang.
		“RGB-T Object Tracking:Benchmark and Baseline”, ArXiv, 2018. Submitted to Pattern Recognition (PR), 2019. [[paper][16]][[project][17]]
	- Download Link [[Google drive][18]]
	- Papers using this dataset
		- Yabin Zhu, Chenglong Li, Yijuan Lu, Liang Lin, Bin Luo, Jin Tang.
		“FANet : Quality-Aware Feature Aggregation Network for RGB-T Tracking”, 2018 (**PR/SR: 76.4/53.2**)
		- Xingchen Zhang, Gang Xiao, Ping Ye, Dan Qiao, Shengyun Peng.
		  "SiamFT: A Feature-level Fusion Tracking Method Using Fully Convolutional Siamese Networks Based on Visible and Infrared Sequences". ICCV 2019 (submitted).(**PR/SR:65.9/44.8**)
		- Xingchen Zhang, Gang Xiao, Ping Ye, Dan Qiao, Junhao Zhao, Shengyun Peng.
		  "Object Fusion Tracking Based on Visible and Infrared Images Using Fully Convolutional Siamese Networks". Fusion 2019 (Submitted).(**PR/SR:61.0/42.8**)
		- Xingming Zhang, Xuehan Zhang, Xuedan Du, Xiangming Zhou, Jun Yin.
		"Learning Multi-domain Convolutional Network for RGB-T Visual Tracking." CISP-BMEI 2018.（**PR/SR:61.7/38.7**）
	- Results

## Results
### GTOT
	Name       | PR   | SR   | Year | Author     |  Type    | FPS |
	FANet      | 88.5 | 69.8 | 2018 | Li et al.  | DL-based | 1.3 |
	Fusing two | 85.2 | 62.6 | 2018 | Li et al.  | DL-based | 15  |
	Weighted   | 85.12| 62.8 | 2017 | Li et al.  |          |  5  |
	Cross-modal| 82.7 | 64.3 | 2018 | Li et al.  |          |  8  |
	Fast RGB-T | 77   | 63.2 | 2019 | Zhai et al.| CF-based | 227 |
	SCCF       | 85   | 68.1 | 
### RGBT210
	Name       | PR   | SR   | Year | Author     |  Type    | FPS |
	Fast RGB-T | 52.9 | 36.6 | 2019 | Zhai et al.| CF-based | 227 |
### RGBT234
	Name         | PR   | SR   | Year |Author       |  Type    | FPS |
	SiamFT       | 65.9 | 44.8 | 2019 | Zhang et al.| DL-based | 25+ |
	Multi-domain | 61.7 | 38.7 | 2018 | Zhang et al.| DL-based |     |
	

## Distinguished Researchers & Teams
- [Chenglong Li][19], Anhui University, China
- Xiangyuan Lan

[1]:	https://www.sciencedirect.com/science/article/pii/S0925231219300347
[2]:	https://ieeexplore.ieee.org/document/8643077
[3]:	https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8485393
[4]:	https://www.sciencedirect.com/science/article/pii/S0925231217318271
[5]:	https://www.sciencedirect.com/science/article/pii/S0923596518304892
[6]:	https://link.springer.com/chapter/10.1007%2F978-3-319-27674-8_6
[7]:	https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7577747
[8]:	https://docs.google.com/uc?id=0B-Z6TyBF2ceIZ0c1anVhaHQ3MFk&export=download
[9]:	https://pan.baidu.com/s/1QNidEo-HepRaS6OIZr7-Cw
[10]:	https://www.sciencedirect.com/science/article/pii/S0925231217318271
[11]:	https://www.sciencedirect.com/science/article/pii/S0925231219300347
[12]:	https://dl.acm.org/citation.cfm?id=3123289
[13]:	https://drive.google.com/file/d/0B3i2rdXLNbdUTkhsLVRwcTBTMlU/view
[14]:	https://pan.baidu.com/s/1qXDAq0O#list/path=%2F
[15]:	https://www.sciencedirect.com/science/article/pii/S0925231219300347
[16]:	https://arxiv.org/pdf/1805.08982.pdf
[17]:	https://sites.google.com/view/ahutracking001/
[18]:	(https://drive.google.com/open?id=1ouNEptXOgRop4U7zYMK9zAp57SZ2XCNL)
[19]:	http://cs.ahu.edu.cn/7d/82/c11202a163202/page.htm