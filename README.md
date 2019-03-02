# DiscreteProbaStats
Samples generations using discrete probability and Kolmogorov-Sirmnov test

Example. A Discrete Uniform (from 0 to 10) sample of size 1000 :

`TestSampleUniform(1000, 10); `

Will output

`
data={5,8,2,5,8,9,9,9,8,1,2,6,1,2,10,3,9,5,8,7,4,8,0,2,9,8,2,0,4,2,1,1,5,6,8,10,3,6,8,5,7,5,8,9,9,9,0,9,5,10,4,0,1,1,6,8,7,10,6,0,6,8,4,6,10,0,1,6,5,10,10,3,7,2,0,10,10,1,4,0,7,3,5,5,9,0,0,4,10,0,2,4,10,8,9,9,0,2,9,8,7,5,4,6,10,0,4,9,0,6,9,6,6,6,3,3,3,10,8,10,0,8,6,4,7,5,4,9,3,2,10,7,2,6,3,2,9,10,5,8,7,1,3,3,2,6,8,3,5,6,6,0,5,10,8,10,10,10,9,4,7,5,5,9,7,1,4,0,3,0,4,4,4,10,2,10,4,2,2,1,8,0,4,8,6,9,2,2,8,4,3,10,0,0,1,2,6,5,7,0,2,8,0,4,2,2,6,6,7,9,6,8,7,8,7,7,0,8,2,8,10,2,2,9,8,5,3,4,8,0,3,9,5,2,10,10,10,10,5,4,3,6,5,10,9,6,2,3,3,4,1,8,3,10,1,10,6,1,6,7,9,2,8,7,5,7,2,5,9,8,7,0,2,8,5,3,7,2,0,2,2,0,0,3,10,5,6,6,1,10,3,8,4,9,6,0,9,9,5,1,3,8,4,6,8,0,6,5,4,8,3,3,0,3,5,8,2,4,7,10,0,6,4,10,4,10,7,4,2,5,4,8,8,9,10,5,7,5,6,10,10,1,1,3,6,10,7,0,3,8,9,5,2,5,1,7,4,5,1,8,3,1,3,10,3,5,6,2,4,10,1,7,8,8,0,9,5,0,3,5,2,6,0,4,7,10,6,2,8,2,1,2,4,8,6,8,8,2,10,1,4,5,7,3,7,1,7,4,4,2,2,3,1,7,6,8,0,9,3,4,9,3,4,1,9,10,3,10,1,2,1,3,0,2,0,7,10,8,8,5,3,1,8,5,10,8,0,8,2,9,8,10,9,6,2,0,0,5,5,7,8,7,3,2,1,10,3,9,6,9,8,3,1,8,0,8,5,10,2,0,9,6,8,3,4,2,4,4,0,0,7,4,2,1,8,6,9,6,4,0,5,2,1,3,0,4,8,0,5,4,5,1,3,4,8,2,10,10,8,10,5,9,8,6,2,3,0,0,0,5,9,10,6,1,6,7,4,4,3,0,4,4,9,6,5,5,1,9,3,5,7,9,8,4,6,7,4,6,1,7,4,8,10,0,6,6,6,1,9,0,9,5,7,8,6,1,10,2,0,7,2,2,7,6,9,10,1,1,6,9,3,8,3,6,7,7,4,9,0,9,9,10,10,2,7,1,2,0,9,4,8,2,5,4,4,1,0,4,2,6,4,5,6,10,7,0,2,0,1,9,7,1,1,1,9,2,3,4,9,7,8,1,3,1,1,1,2,9,2,5,7,10,6,5,5,4,4,0,5,7,10,2,9,10,8,6,0,4,6,2,9,6,5,5,9,3,1,4,8,6,8,3,9,6,2,7,5,7,7,4,9,2,9,2,8,5,2,3,4,5,1,9,3,10,7,0,5,1,6,1,2,10,3,10,9,6,3,2,8,0,1,4,7,2,3,6,7,3,8,3,0,9,0,2,5,10,10,9,10,1,2,3,0,5,1,9,10,10,3,1,1,0,5,4,3,7,2,1,6,0,4,1,3,3,1,4,10,0,5,10,6,5,3,6,8,9,4,1,1,5,7,8,10,6,1,0,3,7,9,8,7,9,2,9,8,1,10,8,3,7,10,9,4,4,5,7,7,10,6,5,3,0,0,1,4,7,2,8,1,1,0,3,1,7,2,8,2,5,9,7,9,6,8,4,6,8,3,6,1,5,3,4,0,3,4,6,9,1,4,1,10,2,6,2,7,6,7,7,1,8,4,1,1,9,7,7,3,7,6,7,3,7,6,6,8,6,2,9,3,6,9,1,1,7,8,6,0,6,7,10,0,6,4,4,1,2,3,1,6,8,3,2,5,7,8,2,7,0,4,0,4,9,4,5,9,3,0,4,1,1,7,7,10,7,7,8,2,2,5,6,3,1,2,6,3,7,6,4,9,5,10,10,1,7,5,1,1,9,5,8,1,9,0,5,0,6,2,9,0,0,0,4,5,8,8,3,7,9,2,1,7,6,5,6,2,7,6,3,1,5,6,4,7,7,4,4,0,7,5,7,4,8,3,9,5,5,4,4,9,2};
Histogram[data,{1}]
ProbabilityPlot[data,DiscreteUniformDistribution[{0,10}]]
DistributionFitTest[data,DiscreteUniformDistribution[{0,10}],{"TestStatisticTable", "KolmogorovSmirnov"}]
Print["Discrete KolmogorovSmirnov:0.009818182 Test:0.043007 => Accepted alpha=0.05"]
`

Mathematica code can be tested online at https://develop.wolframcloud.com
