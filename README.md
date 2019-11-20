# pruebaD

Nada más probando comandos github.

# Anexo scripts utilizados en R 

library(data.table)

#vcf
file = "~/Documents/2020_1/Clase_Camille/Mi_nuevo_repo/Arteaga_et_al_2016/Data/new_final_26_march.vcf"

#tabfile = "/home/duhyadi/Downloads/Galaxy51-[Convert_on_data_50](original).tabular"
#csvfile= "/home/duhyadi/Documents/2020_1/Clase_Camille/Ultimate_issue/Deleterious-alleles-in-landraces-of-maize/Arteaga_et_al_2016/Meta/maizteocintle_SNP50k_meta_extended.csv"

#tabulardata <-fread(tabfile)
vcffile <- fread(file)
select_colum<- fread(file, select = c("5_maiz_12","6_maiz_41"))

dfmaiz <- read.table(csvfile, header = TRUE, sep=',')





install.packages("remotes")
remotes::install_github("shankarkshakya/mypackage")



vcf2nexus(vcf, file = "file.nex")






my_df$column[which(my_df$column == "1/0)] <- "M"
my_df$column[which(my_df$column == "0/1)] <- "R"


library(dplyr)

#Filtrar resultados con dplyr


# Clase de ALicia, trabajo en equipo (nov_10_19)

#Cargar el archivo 
my_dir <- "/home/duhyadi/Downloads/"
tab <-read.table(file)
olotillo <- filter(dfmaiz, Race=="Olotillo")

setwd(my_dir)
read.table(my_dir)



#vcf
file = "~/Documents/2020_1/Clase_Camille/Mi_nuevo_repo/Arteaga_et_al_2016/Data/new_final_26_march.vcf"



library(remotes)
library(mypackage)


#vcf
vcf2nexus(file, file = "vcf_in_nex.nex")



