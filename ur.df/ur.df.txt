# Olah Data Semarang 
# WhatsApp : +6285227746673 
# IG : @olahdatasemarang_ 
# Augmented Dickey-Fuller Test Unit Root Test Use ur.df (urca) With (In) R Software 
install.packages("urca") 
library("urca") 
ur.df = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ur.df/main/ur.df/ur.df.csv",sep = ";") 
# Estimation Augmented Dickey-Fuller Test Unit Root Test Use ur.df (urca) With (In) R Software 
attach(ur.df)
ur.df <- ur.df(y = ur_df, lags = 3, type = 'trend')
summary(ur.df)
# Augmented Dickey-Fuller Test Unit Root Test Use ur.df (urca) With (In) R Software
# Olah Data Semarang 
# WhatsApp : +6285227746673 
# IG : @olahdatasemarang_ 
# Finished