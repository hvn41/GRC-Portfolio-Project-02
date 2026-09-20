# **Risk Assessment: VPN Compromise and XML Command Abuse** 

## **Roles & Responsibilities** 

Applies to: 

- All employees, contractors, third-party users using elevated or administrative privileges 

- SOC Analyst 

- IT System Administrator 

- GRC Analyst 

- Information Security Manager 

## **Definitions** 

- Likelihood: 1 (Low), 2 (Medium), 3 (High) 

- Impact: 1 (Minor), 2 (Moderate), 3 (Severe) 

- Overall risk rating: Likelihood × Impact 

   - 1 – 2: Low Risk (Green) 

   - 3 – 4: Medium Risk (Yellow) 

   - 6 – 9: High Risk (Red) 

## **Risk Register** 

|Risk<br>ID|Risk<br>Description|Inherent<br>Likelihoo<br>d|Inherent<br>Impact|Inhere<br>nt<br>Rating|Controls|Residual<br>Likelihoo<br>d|Residual<br>Impact|Residua<br>l Rating|
|---|---|---|---|---|---|---|---|---|
|RSK<br>-01|Attackers<br>gain<br>unauthorize<br>d network<br>access via<br>compromis<br>ed<br>credentials<br>(e.g.,<br>credential<br>stuffing,<br>phishing).|3 (High)|3<br>(Severe)|9<br>(High)|MFA and<br>30-minute<br>incident<br>block SLA|1 (Low)|2<br>(Moderat<br>e)|2 (Low)|
|RSK<br>-02|Authorized<br>or<br>compromis<br>ed accounts<br>execute<br>unauthorize<br>d shutdown<br>commands,<br>causing SLA<br>breaches.|2<br>(Medium<br>)|3<br>(Severe)|6<br>(High)|Secondary<br>verification<br>(Maker-<br>Checker)<br>and XML<br>Requests<br>Rate-<br>Limiting|1 (Low)|3<br>(Severe)|3<br>(Mediu<br>m)|
|RSK|Employees|3(High)|2|6|Enforceme|1(Low)|2|2(Low)|



|-03|retain<br>excessive<br>privileges or<br>compromis<br>ed XML<br>credentials<br>remain<br>active post-<br>incident.|(Moderat<br>e)|(High)|nt of Least<br>Privilege<br>and<br>immediate<br>credential<br>rotation<br>upon<br>suspected<br>compromis<br>e.|(Moderat<br>e)|
|---|---|---|---|---|---|



## **Risk-Based Decision** 

- All identified inherent high risks have been reduced to acceptable residual level (Low - Medium). 

- The remaining residual risk regarding internal XML command abuse (Medium) must be formally acknowledged and signed off by Information Security Manager. 

- Annual review and continuous log monitoring are highly recommended to maintain operating effectiveness. 

