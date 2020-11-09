[![Build Status](https://travis-ci.com/ssm29njit/calculator601SJ.svg?branch=master)](https://travis-ci.com/ssm29njit/calculator601SJ)

# Calculator Project
Docker file, Travis-ci, requirements.txt, src and test folders

## Mathematical Functions
def add (self, x, y)
def divide(self, x, y)
def minus(self, x, y)
def multiply(self, x, y)
def sqrt(self, x)
def square(self, x)
def sumList(self, lst)

## Random Generator
def generateRandomList(self, n, low, high)
def generateRandomNumber(self, low, high)
def generateRandomSeedNumber(self, seed, low, high)
def selectRandomFromList(self, lst)
def selectRandomNList(self, lst, n)
def selectRandomNListSeed(self, lst, n, seed)
def selectRandomwithSeed(self, lst)

## Statistical Calculator
def mean(self, lst)
def mode(self, lst)
def stdev(self, lst)
def variance(self, lst)
def z_score(self, x, lst)

## CSV Reader
def readFile(self)

## Helper
def validateListInput(func)
def validateNumberInput(func)

## Sample Calculator
def cohran(self, zScore, p, e)
def confidenceInterval(self, width, p, zscore)
def confidenceIntervalSmaple(self, mean, numberofObservation, std, zscore)
def marginOfError(self, populationSize, populationPortion, z_score)
def simpleRandomSampling(self, size, lst)
def smapleSize(self, W, cL, p)
