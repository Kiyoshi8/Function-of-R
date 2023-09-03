# Function-of-R

The Unifrom Distribution

Description
These functions provide information about the uniform distribution on the interval from min to max. dunif gives the density, punif gives the distribution function qunif gives the quantile function and runif generates random deviates.

# Usage
dunif(x, min = 0, max = 1, log = FALSE)
punif(q, min = 0, max = 1, lower.tail = TRUE, log.p = FALSE)
qunif(p, min = 0, max = 1, lower.tail = TRUE, log.p = FALSE)
runif(n, min = 0, max = 1)

Arguments

x, q	
vector of quantiles.

p	
vector of probabilities.

n	
number of observations. If length(n) > 1, the length is taken to be the number required.

min, max	
lower and upper limits of the distribution. Must be finite.

log, log.p	
logical; if TRUE, probabilities p are given as log(p).

lower.tail	
logical; if TRUE (default), probabilities are P[X \le x]P[X≤x], otherwise, P[X > x]P[X>x].
