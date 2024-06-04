# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit a SemiParametric regression Model Use Package SemiPar With (In) R Software
install.packages("SemiPar")
library("SemiPar")
SemiPar = read.csv("https://raw.githubusercontent.com/timbulwidodostp/SemiPar/main/SemiPar/SemiPar.csv",sep = ";")
# Estimation Fit a SemiParametric regression Model Use Package SemiPar With (In) R Software
attach(SemiPar)
SemiPar <- spm(Denpendent~f(Indenpendent))
plot(SemiPar)
summary(SemiPar)
# Fit a SemiParametric regression Model Use Package SemiPar With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished