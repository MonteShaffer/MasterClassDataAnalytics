FREE Master Class in Data Analytics using R
--------------------------------------------------
A gift to you.

Reciprocity is welcome, if you feel so inclined.

--

monte

{x:


--------------------------------------------------

Monte J. Shaffer
Ph.D. Marketing
M.S. Statistics 
M.B.A. Marketing Research
B.A. Mathematics (minors Physics/Spanish)

--------------------------------------------------
PAYPAL:  		monte@mshaffer.com

BUYMECOFFEE:	https://www.buymeacoffee.com/mshaffer

BLOCK-CHAIN:	... figure out bitcoin wallet ...
--------------------------------------------------

YOUTUBE:		https://www.youtube.com/playlist?list=PLeEHWh64fPO9AraJckkHMSy_vIrl70mZV
				https://bit.ly/39ar8q0

--------------------------------------------------

LINKEDIN:		https://www.linkedin.com/in/monte-shaffer-5a906a1/
VITAE:			https://www.mshaffer.com/arizona/
DICTIONARY:		https://1828.mshaffer.com/
COLORS:			https://colors.mshaffer.com/

--------------------------------------------------

		00.001 	Introduction to Master Class [2:53]
					ROYALTY-FREE SOUNDS:  https://www.bensound.com/ [hey]
					
					
UNIT 01: WORKSPACE ENVIRONMENT 
						
		01.001	Introduction (Windows 10), Reflection Journal (Engineering Notebook) [14:32]
					ROYALTY-FREE SOUNDS:  https://www.bensound.com/ [newdawn]
							
								https://www.amazon.com/dp/B07D2R3JRD/
								
					
		01.010 	Install RGui, Rtools, RStudio [07:22]
					ROYALTY-FREE SOUNDS:  https://www.bensound.com/ [creativeminds]
					
						[0:50] 	https://cran.r-project.org/bin/windows/base/
							https://cran.r-project.org/bin/windows/base/R-4.1.1-win.exe
							
						[2:04]	https://cran.r-project.org/bin/windows/Rtools/
							https://cran.r-project.org/bin/windows/Rtools/rtools40v2-x86_64.exe
						
						
						[5:06]	https://www.rstudio.com/products/rstudio/download/#download
							https://download1.rstudio.org/desktop/windows/RStudio-1.4.1717.exe
		
		01.030	Install Notepad++, Gitbash, Setup Github [12:59]
					ROYALTY-FREE SOUNDS:  https://www.bensound.com/ [memories]
					
						[0:50]	https://github.com/notepad-plus-plus/notepad-plus-plus/releases/download/v8.1.4/npp.8.1.4.Installer.x64.exe

						https://github.com/git-for-windows/git/releases/download/v2.33.0.windows.2/Git-2.33.0.2-64-bit.exe

							- Create Account
							- Create Repository ... MasterClassDataAnalyticsParticipant... public, readme, ignore 'R' and MIT							
							- Add Keys
									#  git config --global user.email "monte.shaffer@gmail.com"
									#  git config --global user.name "MonteShaffer"
									# ssh-keygen -t rsa -b 4096 -C "monte.shaffer@gmail.com" # already done "-o"
									# ssh-agent -s
									# ssh -vT git@github.com
									# ssh -T git@github.com
							- CLONE
									git clone https://github.com/MonteShaffer/MasterClassDataAnalytics.git
									git clone https://github.com/MonteShaffer/MasterClassDataAnalyticsParticipant.git
																# Change this to YOUR username ... you will make changes to your REPOSITORY
							- MAKE EDITS
							- COMMIT
							- PUSH
								git remote set-url origin git@github.com:MonteShaffer/MasterClassDataAnalyticsParticipant.git
																# Change this to YOUR username ... you will make changes to your REPOSITORY
								 git add .
								 git status
								 git commit -m "hello world"
								 git push -u origin HEAD:main
		
		01.060	Install Python, Java Runtime Environment, XAMPP (mysql and php) [7:00]
					ROYALTY-FREE SOUNDS:  https://www.bensound.com/ [anewbeginning]
					
					https://www.python.org/downloads/release/python-397/
						https://www.python.org/ftp/python/3.9.7/python-3.9.7-amd64.exe
		
					[2:06]	https://www.java.com/download/ie_manual.jsp
						https://javadl.oracle.com/webapps/download/AutoDL?BundleId=245029_d3c52aa6bfa54d3ca74e617f18309292
		
					[3:25]	https://www.apachefriends.org/download.html
						https://www.apachefriends.org/xampp-files/8.0.10/xampp-windows-x64-8.0.10-0-VS16-installer.exe
		
						/c/_git_/github/MonteShaffer/DataWar
						git clone https://github.com/DataWar/-code-.git

								C:\_git_\github\MonteShaffer\DataWar\-code-\run points to http://localhost/run/
								
								
								C:\xampp\apache\conf\httpd.conf line 248-ish
								
										Alias "/run" "C:/_git_/github/MonteShaffer/DataWar/-code-/run"
										<Directory "C:/_git_/github/MonteShaffer/DataWar/-code-/run">
											AllowOverride All
											Require all granted
										</Directory>
		

UNIT 02: HELLO WORLD
		02.001	Introduction
		02.010 	Folder Organization, First .Rmd Notebook 	(02.010_hello-world-notebook/hello-world.Rmd)
		02.020	Writing Functions in vector form 			(02.020_vectors/standardize.Rmd)
		02.030	Writing 'is' functions 						(02.030_is/is-odd.Rmd)							# is.odd, is.even (is.null and is.na)
															(02.030_is/is-zero.Rmd							# is.positive, is.negative, is.zero
		02.040	Writing functions for 'stats' module		
															(02.040_stats/an-overview.Rmd)					# built-in functions
															(02.040_stats/mean-variance.Rmd)				# mean and variance
															(02.040_stats/median-MAD-sort.Rmd)				# median and MAD (sort)
															(02.040_stats/min-max.Rmd)						# min and max (which.min vs whichMin)
															(02.040_stats/mode.Rmd)							# mode and notMode
															(02.040_stats/range-scale-outliers.Rmd)		 	# IQR (interquartile range), z-scores, outlier detection
		02.050	Writing function 'stats.summary'
		
		02.060	Problem: 	PERSONALITY.cleanupData (cleanup PERSONALITY data)
		02.065	Solution: 	PERSONALITY.cleanupData (cleanup PERSONALITY data)
		
		02.073	'color' theory (02-colors.Rmd)
		
		02.080	Problem:  	HANDSHAKE and HANDSHAKE.draw
		02.085	Solution:  	HANDSHAKE and HANDSHAKE.draw
		
		
UNIT 02: DISTANCE and CORRELATION
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
UNIT 02: HELLO WORLD		
		
		
		(02.040_stats) ... mean, sd, mode, median [sort], mad, IQR, IXR
																		stats.mean.vector ... stats.mean.raw
																		min/max ... which ... stats.summary
																		
		02.042	Task: stats.sampleVariance [method = naive vs 2pass]
					https://en.wikipedia.org/wiki/Algorithms_for_calculating_variance
					
		02.044	Task: stats.mode and stats.notMode
		02.046	Task: stats.mean and stats.median ('prime' module)
		02.048	Task: stats.summary
		02.050	Problem: 	PERSONALITY.cleanupData (cleanup PERSONALITY data)
		02.055	Solution: 	PERSONALITY.cleanupData (cleanup PERSONALITY data)
		02.066	'color' theory (02-colors.Rmd)
		02.060	Problem:  	HANDSHAKE and HANDSHAKE.draw
		02.065	Solution:  	HANDSHAKE and HANDSHAKE.draw
		
		
100 days
40 hours of lecture ... 32 sessions
160 hours of work ... on path to 10,000		
		
		
UNIT 02: DISTANCE (IMDB)

radial distance from SQL query

new york city vs chicago 

distance compare bivariate WILL v DENZEL and multivariate
distance compare temperature WIKI for two cities



UNIT 03: CLUSTERING

kmeans vs hclust ... 

UNIT 04: CORRELATION

UNIT 05: PCA

UNIT 06: EFA / CFA (PERSONALITY)

UNIT 07: CLASSIFYING (MNIST)

UNIT 08: NLP (GRIMM)

UNIT 09: EIGENRANK (NHL)





UNIT 10:  TRADING FEATURES (5 min day trading)








