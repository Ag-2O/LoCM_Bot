# LoCM_Bot
Strategy Card Game AI Competition 2021 に提出したbot  
https://legendsofcodeandmagic.com/COG21/  

# 概要
基本的にはニューラルネットワークに、あるゲームの状態(体力やカードの効果など)の値を入力して、出力される勝率を基に行動を決定します。
制限時間内であれば探索して連続した行動を返します。間に合わない場合は、可能な行動をランダムに並べて返します。
