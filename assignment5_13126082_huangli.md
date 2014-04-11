Pairwise Comparisons between Testing and other QA Alternatives
=================================
Huang Li (13126082)

----------------------------

###QA alternatives compared to testing

	- defect prevention (DP),
		
	- inspection,
		
	- formal verification (FV),
		
	- fault tolerance (FT),
		
	- failure containment (FC)
	
###Tesing VS. Defect Prevention

-	*Applicability to maintenance*
	-	Defect prevention: Not applicable
	-	Testing: Applicable to a limited degree
-	*Objects QA activities applied on*
	-	Defect prevention: Implementation activities 
	-	Testing: executable code
-	*Applicability to development phases*
	-	Defect prevention: Implementation (req/spec/design/coding)	-	Testing: testing phase and after
-	*Expertise levels and background knowledge*
	-	Defect prevention: medium to high expertise levels
	-	Testing: low to high expertise levels
-	*Defect perspectives*	
	-	Defect prevention: errors and error sources detected in defect prevention but reduced fault injection in followup
	-	Testing: failures detected in testing but (failure-causing) faults fixed in followup
-	*Problem types*
	-	Defect Prevention: systematic errors or conceptual mistakes
	-	Testing: dynamic failures and related faults
-	*Cost*
	-	Defect Prevention: low
	-	Testing: medium(low to high)
	
###Tesing VS. Inspection

-	*Applicability to maintenance*
	-	Both are applicable to a limited degree
-	*Objects QA activities applied on*
	-	Inspection: design, code, and other software artifacts 
	-	Testing: executable code
-	*Applicability to development phases*
	-	Inspection: All
	-	Testing: testing phase and after
-	*Expertise levels and background knowledge*
	-	Inspection: low to medium expertise levels
	-	Testing: low to high expertise levels
-	*Defect perspectives*	
	-	Inspection: faults detected in inspection but fault removal in followup
	-	Testing: failures detected in testing but (failure-causing) faults fixed in followup
-	*Problem types*
	-	Inspection: static and localized faults
	-	Testing: dynamic failures and related faults
-	*Cost*
	-	Inspection: low to medium
	-	Testing: medium(low to high)

###Tesing VS. Formal Verification

-	*Applicability to maintenance*
	-	Both are applicable to a limited degree
-	*Objects QA activities applied on*
	-	Formal Verification: design, code, with formal specification 
	-	Testing: executable code
-	*Applicability to development phases*
	-	Formal Verification: design/coding
	-	Testing: testing phase and after
-	*Expertise levels and background knowledge*
	-	Formal Verification: high expertise levels and formal training
	-	Testing: low to high expertise levels
-	*Defect perspectives*	
	-	Formal Verification: absence of faults in formal verification but fault absence verified in followup
	-	Testing: failures detected in testing but (failure-causing) faults fixed in followup
-	*Problem types*
	-	Formal Verification: logical faults(indirectly)
	-	Testing: dynamic failures and related faults
-	*Cost*
	-	Formal Verification: high
	-	Testing: medium(low to high)

###Tesing VS. Fault Tolerance

-	*Applicability to maintenance*
	-	Fault Tolerance: Applicable, but designed/implemented during development
	-	Testing: As related to reported field failures, applicable to a limited degree
-	*Objects QA activities applied on*
	-	Fault Tolerance: operational software system 
	-	Testing: executable code
-	*Applicability to development phases*
	-	Fault Tolerance: in-field operation
	-	Testing: testing phase and after
-	*Expertise levels and background knowledge*
	-	Fault Tolerance: high expertise levels and dynamic systems
	-	Testing: low to high expertise levels
-	*Defect perspectives*	
	-	Fault Tolerance: local failures detected in fault tolerance but global failures avoided in followup
	-	Testing: failures detected in testing but (failure-causing) faults fixed in followup
-	*Problem types*
	-	Fault Tolerance: operational failures in small areas
	-	Testing: dynamic failures and related faults
-	*Cost*
	-	Fault Tolerance: high
	-	Testing: medium(low to high)

###Tesing VS. Failure Containment

-	*Applicability to maintenance*
	-	Failure Containment: Applicable, but designed/implemented during development
	-	Testing: As related to reported field failures, applicable to a limited degree
-	*Objects QA activities applied on*
	-	Failure Containment: system with potential accidents 
	-	Testing: executable code
-	*Applicability to development phases*
	-	Failure Containment: in-field operation
	-	Testing: testing phase and after
-	*Expertise levels and background knowledge*
	-	Failure Containment: high expertise levels and safety,embedded systems
	-	Testing: low to high expertise levels
-	*Defect perspectives*	
	-	Failure Containment: accidents detected in failure containment but hazard resolution and damage reduction in followup
	-	Testing: failures detected in testing but (failure-causing) faults fixed in followup
-	*Problem types*
	-	Failure Containment: accidents and related hazards
	-	Testing: dynamic failures and related faults
-	*Cost*
	-	Failure Containment: highest
	-	Testing: medium(low to high)