# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Differential Item Functioning (DIF) detection using non-linear regression method Use difNLR With (In) R Software
install.packages("difNLR")
library("difNLR")
require(stats)
# Estimate Differential Item Functioning (DIF) detection using non-linear regression method Use difNLR With (In) R Software
difNLR = read.csv("https://raw.githubusercontent.com/timbulwidodostp/difNLR/main/difNLR/difNLR.csv", sep = ";")
difNLR_ <- difNLR[, 2:21]
group <- difNLR[, "group"]
difNLR <- difNLR(difNLR_, group, focal.name = 1, model = "3PLcg")
difNLR
# Differential Item Functioning (DIF) detection using non-linear regression method Use difNLR With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished