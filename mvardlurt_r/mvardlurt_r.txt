# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Multivariate Autoregressive Distributed Lag (ARDL) Unit Root Test Use mvardlurt With (In) R Software
install.packages("mvardlurt")
library("mvardlurt")
# Estimation Multivariate Autoregressive Distributed Lag (ARDL) Unit Root Test Use mvardlurt With (In) R Software
mvardlurt_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mvardlurt_r/main/mvardlurt_r/mvardlurt_r.csv",sep = ";")
y <- mvardlurt_r$mvardlurt
x <- mvardlurt_r$mvardlurt_
mvardlurt <- mvardlurt(y, x, case = 3, reps = 200)
mvardlurt
mvardlurt_ <- mvardlurt(y, x, fixlag = c(2, 2), reps = 200)
mvardlurt_
# Multivariate Autoregressive Distributed Lag (ARDL) Unit Root Test Use mvardlurt With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished