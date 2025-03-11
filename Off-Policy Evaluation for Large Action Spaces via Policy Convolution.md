Off-Policy Evaluation for Large Action Spaces via Policy Convolution

https://arxiv.org/abs/2310.15433

- 行動数1万まで結果示している。1万でも割と良い
- offCEMや他の行動数が多い場合の先行研究もこのフレームワークの特殊ケースと主張
- 複数のconvolution関数を提案。問題や状況により最適なものは異なった。
- convolution により似たアクションでのログデータを活かすイメージかな。それにより common supportが満たされない場合の誤差抑制。また、バリアンス抑制