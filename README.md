# WISA_motionmag_tutorial
 This is a repository made as part of the workshop [Waves and Instabilities in the Solar Atmosphere](https://www.wisa2023.org/) held in June 2023 at Northumbria University, UK. This tutorial, ``Motion magnification and its application to solar data'', was given by [**Dr Tim Duckenfield**](https://orcid.org/0000-0003-3306-4978).

 For questions, comments please email [`tim.duckenfield@northumbria.ac.uk`](mailto:tim.duckenfield@northumbria.ac.uk).

 There are several notebooks in the repository, I suggest starting with [mm_example.ipynb](https://colab.research.google.com/github/Tduckenfield/wisa_motionmag_tutorial/blob/main/mm_example.ipynb) to get a feel for the the process. Then for further information:
 1.  More detailed explanation behind the underlying DT$\mathbb{C}$WT tranform may be found in [understanding_dtcwt.ipynb](https://colab.research.google.com/github/Tduckenfield/wisa_motionmag_tutorial/blob/main/understanding_dtcwt.ipynb).
 2. An explanation of the motion magnification algorithm, its parameters, and playing around with magnifying a toy datacube can be found in [understanding_mm.ipynb](https://colab.research.google.com/github/Tduckenfield/wisa_motionmag_tutorial/blob/main/understanding_mm.ipynb).
 3. A rough tutorial for downloading some AIA/SDO data, choosing a cutout, and motion magnifying it to search for decayless kink oscillations (as discussed by several of previous speakers!) for yourself may be found in [mm_solardata.ipynb](https://colab.research.google.com/github/Tduckenfield/wisa_motionmag_tutorial/blob/main/mm_solardata.ipynb)

# File IDs
 To do this analysis, you need some images, datacubes and movies. Since they are too large to be kept in this repository (cloning this repository would become very sluggish), I have saved some data in a shared Google drive. 
 One can use [!gdown](https://colab.research.google.com/github/ga642381/ML2021-Spring/blob/main/Colab/Google_Colab_Tutorial.ipynb#scrollTo=XztYEj0oD7J3) to download specific files into our current working directly, if one knows the user id. Here is a list of some useful datacubes you may wish to take a look at.
* daphne.jpg = 1waPbCvz8Tkhyzzg3f968TDgjxsUaIN_D
* mandrill.npz = 1bDU4_hbyGZZ-HDMEJo591prdwfRwyxOl
* sergey.mp4 = 1l8HjifR4t52D16tx2NGtk0FoxxD3wWDp
* guitar.mp4 = 1jK4K3hASDLyV1_IL8i7aHN0Bw_NmPY8Q
* daphne_sleeping_compressed.mp4 = 1RHOMVPS0I4untNWh52_9TgoOccgUx2DD
* daphne_garden.MOV = 1kEO4P9EawBvTCj8zNE1yun5uQllaSYJD   # Careful, this is too large to MM in colab
* bye.mp4 = 1Sofe9IFkTzVFMGuAlmOw4SnNDSFQQP5v

If you are struggling to get the codes to run, some outputs are also stored here.
* daphne_mm.mp4 = 1Cl0lD51Y0Tb5KeCHHYj2Qtac7gYyszbt
* aia.lev1_euv_12s.2023-06-10T232959Z.171.image.fits = 1InSb8x0LoJTdyYbzRe2igtyWa7tJxF1R
* orig_fits.zip = 1aWmxzJRmjQjU3GKn7m3CneAWYK-hYNga # This contains all my cutout FITS files
* mm_fits.zip = 18-7V5KAqepQWVa7fqNvhpI4AIw_iYTvZ # This contains all my cutout FITS files
* 20230611_sunmaps.mp4 = 1K5XrbapQ1MUYt7nsUkY_sNboTne-zz-t
* 20230611_171_magk5w120.npy = 1ZLTq9wauJNNoO_VBE5AZuHSMCruOBzjp
* 20230611_k5w120_sunmaps.mp4 = 1SF6NKi7SlMUlqrzzvRxearsPbzfrqDeF