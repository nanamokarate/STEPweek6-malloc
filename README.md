# STEPweek6-malloc　challenge


##	malloc challenge result

|            | challenge1 | challenge2 | challenge3 | challenge4 | challenge5 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| First-fit |70% |40% |7% |15% |15% |
| Best-fit |70% |40% |50% |71% |74% |
| Worst-fit |70% |40% |4% |7% |7% |

###	First-fit
十分な大きさを持つ空き領域のうち一番最初に見つかったものを選ぶ

###	Best-fit
十分な大きさを持つ空き領域のうち一番小さいサイズのものを選ぶ

→First-fitよりも無駄がなくなる

###	Worst-fit
十分な大きさを持つ空き領域のうち一番大きいサイスのものを選ぶ

→First-fitよりも無駄が増える

##	実行時間

|            | challenge1 | challenge2 | challenge3 | challenge4 | challenge5 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| First-fit |1528ms |584ms |806ms |9380ms |6616ms |
| Best-fit |8ms |6ms |121ms |25946ms |16975ms |
| Worst-fit |1535ms |506ms |54410ms |548988ms |543775ms |

実行時間もBest-fitが一番早い！
