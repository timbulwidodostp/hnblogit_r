# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit the negative binomial-logit hurdle model (hnblogit) Use hurdle (pscl) With (In) R Software
install.packages("pscl")
library("pscl")
hnblogit_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/hnblogit_r/main/hnblogit_r/hnblogit_r.csv",sep = ";")
# Estimation Fit the negative binomial-logit hurdle model (hnblogit) Use hurdle (pscl) With (In) R Software
hnblogit <- hurdle(y ~ x1 + x2 | x1, data = hnblogit_r, dist = "negbin", zero.dist = "binomial")
summary(hnblogit)
# Fit the negative binomial-logit hurdle model (hnblogit) Use hurdle (pscl) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished