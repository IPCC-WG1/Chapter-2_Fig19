##########################################################################
# ---------------------------------------------------------------------------------------------------------------------
# This is Matlab code to produce IPCC AR6 WGI Figure 2.19
# Creator: Daoyi Gong, Beijing Normal University 
# Contact: gdy@bnu.edu.cn
# Last updated on: June 9th, 2021
# --------------------------------------------------------------------------------------------------------------------
#
# - Code functionality: This script plots the surface wind trends for HadISD, ERA5, CCMP and OAFlux
# - Input data: Annual mean surface wind. Data available: HadISD: https://www.metoffice.gov.uk/hadobs/hadisd/v202_2017f/station_download.html ; ERA5: https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-pressure-levels-monthly-means?tab=form ; CCMP:http://data.remss.com/ccmp/v02.0 ; OAFlux: ftp://ftp.whoi.edu/pub/science/oaflux/wind_v1 
# - Output variables:The code plots the figure as in the report
#
# ----------------------------------------------------------------------------------------------------
# Information on  the software used
# - Software Version: Matlab R2011b
# - Landing page to access the software: https://www.mathworks.com/products/matlab.html 
# - Operating System: Windows 10
# - Environment required to compile and run: >2GB memory, >512GB hard disk 
#  ----------------------------------------------------------------------------------------------------
#
#  License:  Apache 2.0
#
# ----------------------------------------------------------------------------------------------------
# How to cite:
Gulev, S.K., P.W. Thorne, J. Ahn, F.J. Dentener, C.M. Domingues, S. Gerland, D. Gong, D.S. Kaufman, H.C. Nnamchi, J. Quaas, J.A. Rivera, S. Sathyendranath, S.L. Smith, B. Trewin, K. von Schuckmann, and R.S. Vose, 2021: Changing State of the Climate System. In Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change[Masson-Delmotte, V., P. Zhai, A. Pirani, S.L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M.I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, J.B.R. Matthews, T.K. Maycock, T. Waterfield, O. Yelekçi, R. Yu, and B. Zhou (eds.)]. Cambridge University Press, Cambridge, United Kingdom and New York, NY, USA, pp. 287–422, doi:10.1017/9781009157896.004.
# When citing this code, please include both the code citation and the following citation for the related report component:
 https://doi.org/10.5281/zenodo.6339999


########################################################################
