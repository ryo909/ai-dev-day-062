# Day062 Story — Gift Overlap Breaker

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day062専用にテーマをseed固定して再生成時の見た目を安定化
- productivity用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: gift_overlap_assignment
- Mechanic: coverage_assign
- Input/Output: participant_rows -> assignment_board
- Audience Promise: 持っていく物と担当をその場で決められる。
- Publish Hook: 候補・予算・避けたい食材を自分で入れると、かぶりと不足が一画面で見えて担当まで決まる。
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day062｜手土産かぶりほどき
手土産候補のかぶりと不足を整えやすくするためのツールです。
