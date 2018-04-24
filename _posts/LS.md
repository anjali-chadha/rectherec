**Literature Survey :** 

Cross Domain Collaborative Filtering:-
Collaborative Filtering boils down to analyzing the user-item matrix. It can be easily extended with other auxiliary domains under the pretext of common users or common items. 

[B. Li, Q. Yang, and X. Xue, "Can movies and books collaborate? cross-domain collaborative filtering for sparsity reduction," in IJCAI, 2009, pp. 2052-2057.
 "Transfer learning for collaborative filtering via a rating-matrix generative model," in ICML, 2009, pp. 617-624.](https://www.ijcai.org/Proceedings/09/Papers/338.pdf)
 
[W. Pan, E. W. Xiang, N. N. Liu, and Q. Yang, "Transfer learning in collaborative filtering for sparsity reduction," in AAAI, 2010, pp. 230-235.](https://www.aaai.org/ocs/index.php/AAAI/AAAI10/paper/view/1649)

[Y. Zhang, B. Cao, and D.-Y. Yeung, "Multi-domain collaborative filtering," in UAI, 2010, pp. 725-732.](https://arxiv.org/pdf/1203.3535.pdf)
	

Content Based Cross Domain Recommendations:-

Content based CDR models users and items as feature vectors and recommends based on similarity between the two. If users/items are common among different domains the feature vectors can simply be concatenated to incorporate more information.

[Sahebi, Shaghayegh, and Trevor Walker. "Content-Based Cross-Domain Recommendations Using Segmented Models." CBRecSys@ RecSys. 2014.](http://ceur-ws.org/Vol-1245/cbrecsys2014-paper09.pdf)

[Biadsy, Naseem, Lior Rokach, and Armin Shmilovici. "Transfer learning for content-based recommender systems using tree matching." International Conference on Availability, Reliability, and Security. Springer, Berlin, Heidelberg, 2013.](https://arxiv.org/pdf/1305.3384.pdf)

Neural Network based CDRs:-

Multi-View Deep Neural Network-

Content based techniques calculates features to represent users and items. Neural networks are powerful feature extractors and can be effectively used in a multi/cross domain setting.

[Elkahky, Ali Mamdouh, Yang Song, and Xiaodong He. "A multi-view deep learning approach for cross domain user modeling in recommendation systems." Proceedings of the 24th International Conference on World Wide Web. International World Wide Web Conferences Steering Committee, 2015.](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/frp1159-songA.pdf)


Content Boosted Collaborative Filtering:-
Content-based modelling of MV-DNN is used to augement the Collaborative Filtering matrix. The idea is to the correlate the latent-factor matrix of the CF part with the content-modelling of MV-DNN.

[Lian, Jianxun, et al. "CCCFNet: a content-boosted collaborative filtering neural network for cross domain recommender systems." Proceedings of the 26th International Conference on World Wide Web Companion. International World Wide Web Conferences Steering Committee, 2017.](http://delivery.acm.org/10.1145/3060000/3054207/p817-lian.pdf?ip=165.91.13.19&id=3054207&acc=ACTIVE%20SERVICE&key=B63ACEF81C6334F5%2E79B51EFA2DE92FE8%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1524538725_ebb4ce384e81128d1c48f17f492c89da)

In all the above explained methods either there is single or mutiple cross domains. However, there is very little analysis on which domains can help the prediction in the target domain the most. A gap that we seek to fill. 
