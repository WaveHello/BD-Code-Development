# Subroutines that need to be modified

# Done
* DetermineYieldFunctionValue 
DetermineYieldFunctionValue(IntGlo,SigC,c,phi,hyperbolic_a_constant, F)

* CalculateDerivativesYieldFunctAndPlasticPotential
 CalculateDerivativesYieldFunctAndPlasticPotential(Sig,p,J,Lode,S3TA,c,phi,psi, hyperbolic_a_constant, DFDSig,DPPDSig)

* CalculateDerivativesYieldFunctSofteningParameters
CalculateDerivativesYieldFunctSofteningParameters(p,J,Lode,S3TA,c,phi, hyperbolic_a_constant, DFDSP)

* EndOfStepCorrection
EndOfStepCorrection(IntGlo,D1,D2,GG,IPL,F,Sig,DSPDPEq,DEpsPEqDPS,EpsP,c,phi,psi, hyperbolic_a_constant)

* DetermineElasticProportionPegasusMethod
DetermineElasticProportionPegasusMethod(IntGlo,Sig,DSig,DEps,c,phi, hyperbolic_a_constant, YTOL,alpha)

* DetermineDSigAndDEpsP
DetermineDSigAndDEpsP(IntGlo,D1,D2,GG,c,phi,psi,Sig, hyperbolic_a_constant, DEpsPEqDPS,DSPDPEq,DEps,DSig,DEpsP)

* MCSS_Ortiz_Simo_Integration(G, D1, D2, IntGlo, Sig, c, phi, psi, factor, dEps, EpsP, dEpsP, cr, phir, psir, cp, phip, &
      psip, ctol, phitol, psitol, FTOL, max_iterations, hyperbolic_a_constant)

dadc
dadPhi

# Need to be modified




hyperbolic_a_constant

C00P50

# Need to check the derivatives
