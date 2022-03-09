# Tư duy Logic

## Table of Contents

1. Tư duy Logic
	1. Kiến thức cần thiết
	2. Phương pháp làm bài
		1. Lập bảng
		2. Biểu đồ Venn
		3. Suy luận thường
		4. Lựa chọn tình huống

## Kiến thức cần thiết

- **Mệnh đề:** câu khẳng định chỉ đúng/sai. (không phải "?", "!", cầu khiến)
- **Mệnh đề phủ định**: $`P \rightarrow \bar{P}`$ Không phải P
- **Mệnh đề hội:** $P \cap Q$  "P và Q" - **"và"**
- **Mệnh đề tuyển:** $P \cup Q$ "P hoặc Q" - **"hoặc"**
- **Mệnh đề kéo theo:** $P \Rightarrow Q$  "Nếu P thì Q - P su:y ra Q"
- **Mệnh đề đảo của $P \Rightarrow Q$:** là $Q \Rightarrow P$
	- Nếu $P \Rightarrow Q$ là 1 định lý: $P$ gọi là *điều kiện đủ*, $Q$ gọi là *điều kiện cần*.
- **Mệnh đề tương đương:** $P \Leftrightarrow Q$ : "P nếu và chỉ nếu Q"
	- Nếu $P \Leftrightarrow Q$  là 1 định lý: Điều kiện cần và đủ để có P là Q.
- Bảng giá trị:
| P   | Q   | $\bar{P}$ | $\bar{Q}$ | $P \cap Q$ | $P \cup Q$ | $P \Rightarrow Q$ | $P\Leftrightarrow Q$ |
| --- | --- | --------- | --------- | ---------- | ---------- | ----------------- | -------------------- |
| 1   | 1   | 0         | 0         | 1          | 1          | 1                 | 1                    |
| 1   | 0   | 0         | 1         | 0          | 1          | 0                 | 0                    |
| 0   | 1   | 1         | 0         | 0          | 1          | 1                 | 0                    |
| 0   | 0   | 1         | 1         | 0          | 0          | 1                 | 1                    |

- Công thức cần nhớ:
	- $\bar{\exists{x}\in X:P(x)} = \forall{x} \in X: \bar{P(x)}$
	- $\bar{P \cup Q} = \bar{P} \cup \bar{Q}$
	- $(P \Rightarrow Q) = (\bar{Q} \Rightarrow \bar{P}) = (\bar{P} \cup Q) = \bar{P \cap \bar{Q}}$
	- $\bar{\bar{P}} = P$
	- $\bar{\forall{x} \in X : P(x)} = \exists{x} \in X : \bar{P(x)}$
	- $\bar{P \cap Q} = \bar{P} \cup \bar{Q}$
	- $P \Leftrightarrow Q = P\cap Q \cup \bar{P} \cap \bar{Q}$
- Ví dụ:
	- A: "Có ít nhất một người trong lớp tham gia kì thi T.Anh" $\rightarrow \bar{A}$ : "Tất cả mọi người trong lớp đều không tham gia kì thi T.Anh."
	- B: "An biết chơi bóng đá và cả bóng rổ" $\rightarrow \bar{B}$ : "An không biết chơi bóng rổ *hoặc* không biết chơi bóng đá." (B có dạng $P\cap Q$ nên $\bar{B} = \bar{P\cap Q} = \bar{P} \cup \bar{Q}$)
	- C: "Nếu bạn không đi dự bữa tiệc đó thì tôi cũng không đi" a.k.a. "Bạn đi dự bữa tiệc đó hoặc tôi không đi."
	-
