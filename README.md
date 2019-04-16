# isotopomer-rates
Rate model for the production of N2O, using isotopomers as model constraint.
Version 1, Mar 18, 2019

DESCRIPTION:
Uses known values for production of N2O isotopomers to solve for the rates of N2O prodoction from denitrification and hybrid 
N2O production.

INPUT:
Rates of change (nmol/L/day) of each mass of N2O (44,45,46) plus rates of change of each isotopomer (45N2O-alpha, 45N2O-beta).

OUTPUT:
% f(1) = denitrification rate (nmol/L/day)
% f(2) = rate of hybrid production of 45N2O-alpha (nmol/L/day)
% f(3) = rate of hybrid production of 45N2O-beta (nmol/L/day)
% f(4) = rate of hybrid production of 44N2O (nmol/L/day)
% f(5) = nitrification rate (nmol/L/day)
 
AUTHOR:  Colette Kelly (clkelly@stanford.edu)
