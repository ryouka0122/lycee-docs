
# 機械学習と周辺技術との関係

人工知能 → アイディア  
機械学習 → 概念  
深層学習 → 技法  

* 人工知能 AI: Artificial Intelligence
  * 強いAI  
    人間性を持った柔軟な思考を持ったシステムを指す．  
    スターウォーズのC-3POやIBMのWatson，SoftbankのPepperなど
  * 弱いAI  
    ある特定の問題に対してシステム自ら解法を最適化し，答えを導き出す．  
    顔認識や画像分類，動画の自動タグ付けなど

機械学習は弱いAIの中に位置付けられる．  
機械学習には，処理の原理から以下のように分類することができる．  
* 機械学習
  * 記号処理  
    記号処理や記号操作に基づいた技術を利用し処理を行う．  
    テキストマイニングなど  
    * 帰納学習
    * 教示学習
    * 進化的計算
      * 群知能
        * 蟻コロニー最適化法 Ant Colony Optimization
        * 粒子群最適化法 Particle Swarm Optimization
      * 遺伝的アルゴリズム GA: Genetic Algorithm
  * 統計的処理
    学習データを統計的確率によって得られたものであると仮定し，数学的処理を行う．
    * 統計的分析
      * 回帰分析
      * クラスタ分析
      * 主成分分析
    * ニューラルネットワーク NN: Neural-network
    * 深層学習 DL: Deep-learning
      * RNN: Recurrent Neural-network
        * SLTM: Short-Long Term Memory
      * CNN: Convolutional Neural-network

これとは別に，学習手法から次のような分類が出来る．
* 学習方法
  * 教師あり学習  
    画像分類，音声認識
  * 教師なし学習  
    自動分類，クラスタリング
  * 強化学習  
    Q学習，DQN: Deep Q-learning
