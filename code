import pandas as pd
import glob, os

os.chdir("C:/Users/yourUserName/Desktop/yourTestFolder")
results = pd.DataFrame([])

for counter, file in enumerate(glob.glob("searchOnlyByThisSearchTerm*")):
    namedf = pd.read_csv(file, usecols=[0,1,2,3,4,5])
    results = results.append(namedf)

results.to_csv("C:/Users/yourUserName/Desktop/testFolder/combinedfile.csv")
