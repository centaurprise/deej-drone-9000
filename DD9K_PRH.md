# **Product Requirements Hypothesis: Enterprise Aerial Cargo Solution**

**Version 0.1 | Customer Discovery Template | Interview Guide**

---

***Interview Guide Instructions:** Use this template for customer discovery. Fill in blanks over the course of multiple interviews (30 is a good target); no way you’ll answer the whole thing in one. Prioritize 2-5 things you want to ask each interviewee before you kick off the conversation. You should have a plan, but don’t follow it too rigidly in case they guide you somewhere more interesting. Follow decision trees based on responses. Check off inventory items as completed. Synthesize findings into actual PRD only after validation.*

---

## **\[EXS\] Executive Summary**

**Core Hypothesis:** We believe autonomous truck fleet operators face significant challenges in last-mile delivery to remote locations that could be addressed through aerial cargo solutions. This document guides customer discovery to validate whether our capabilities in autonomous navigation could translate to an aerial platform that customers would actually purchase.

**Discovery Objectives:**

* Validate existence and severity of remote delivery pain points  
* Understand willingness to adopt aerial solutions from existing vendor  
* Identify must-have features vs. nice-to-haves  
* Determine acceptable price points and ROI requirements

## **\[PV\] Purpose and Vision Validation**

### **\[PV-01\] Problem Hypothesis Testing**

**We hypothesize that enterprise logistics operators face the following challenges:**

- [ ] Remote locations unreachable by ground transport: \_***% of deliveries***   
- [ ] ***Time-critical deliveries requiring expensive alternatives: $*** annual spend   
- [ ] Environmental mandates restricting current solutions: \_\_\_\_\_\_\_\_\_\_ (specific requirements)

**Interview Questions:**

1. "What percentage of your deliveries face accessibility challenges?"  
   * Customer response: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
2. "What are you currently doing for remote/emergency deliveries?"  
   * Current solution: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Cost per incident: $\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
3. "What sustainability requirements affect your logistics decisions?"  
   * Regulatory requirements: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Board mandates: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Decision Tree:**

* **IF** customer mentions \>$500K annual helicopter costs → **PROBE** frequency, payload sizes, distance requirements  
* **IF** customer has no remote delivery needs → **PIVOT** to disaster response or seasonal surge scenarios  
* **IF** sustainability isn't a priority → **PROBE** cost savings potential, operational efficiency

### **\[PV-02\] Solution Fit Validation**

**Hypothesis:** An aerial cargo solution could solve the speed/range/sustainability trilemma

- [ ] Speed requirement: Delivery within \_\_\_\_\_\_\_ hours   
- [ ] Range requirement: \_\_\_\_\_\_\_ miles typical distance   
- [ ] Sustainability requirement: \_\_\_\_\_\_\_ % carbon reduction mandate

**Interview Questions:**

1. "If you could design the perfect remote delivery solution, what would it look like?"  
   * Must-haves: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Nice-to-haves: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Deal-breakers: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Decision Tree:**

* **IF** speed is critical → **PROBE** "What if it took 2 hours instead of 30 minutes?"  
* **IF** range \>400 miles → **PROBE** "Would hub-and-spoke with ground transport work?"  
* **IF** sustainability crucial → **TEST** "How would biodiesel vs. electric vs. hydrogen rank?"

## **\[TUP\] Target User Discovery**

### **\[TUP-01\] Buyer Persona Validation**

**Hypothesis:** Purchase decisions involve multiple stakeholders

**Stakeholder Mapping Exercise:**

| Role | Name | Pain Points | Decision Power (1-10) | Notes |
| ----- | ----- | ----- | ----- | ----- |
| Economic Buyer | \_\_\_\_\_\_\_ | \_\_\_\_\_\_\_ | \_\_\_\_\_ | \_\_\_\_\_\_\_ |
| Technical Evaluator | \_\_\_\_\_\_\_ | \_\_\_\_\_\_\_ | \_\_\_\_\_ | \_\_\_\_\_\_\_ |
| End User | \_\_\_\_\_\_\_ | \_\_\_\_\_\_\_ | \_\_\_\_\_ | \_\_\_\_\_\_\_ |
| Influencer | \_\_\_\_\_\_\_ | \_\_\_\_\_\_\_ | \_\_\_\_\_ | \_\_\_\_\_\_\_ |

**Interview Questions:**

1. "Walk me through your last major logistics technology purchase"  
   * Process duration: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Key stakeholders: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Decision criteria: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
2. "Who would need to approve an aerial cargo solution?"  
   * Approvers: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Budget threshold requiring board approval: $\_\_\_\_\_\_\_\_\_\_\_\_\_

**Decision Tree:**

* **IF** procurement-led → **PROBE** TCO models, vendor consolidation priorities  
* **IF** user-led → **PROBE** operational pain points, workflow integration  
* **IF** C-suite mandate → **PROBE** strategic initiatives, board reporting metrics

## **\[FR\] Feature Requirements Discovery**

### **\[FR-01\] Propulsion System Preferences**

**Hypothesis:** Customers care more about operational capabilities than specific fuel type

□ Flight duration requirement: \_\_\_\_\_\_\_ hours □ Refueling infrastructure preference: \_\_\_\_\_\_\_ □ Environmental preference ranking: Electric \_\_\_ Biodiesel \_\_\_ Hydrogen \_\_\_ Jet Fuel \_\_\_

**Interview Questions:**

1. "What are your thoughts on different drone power sources?"  
   * Response: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
2. "Do you have existing fuel infrastructure we should consider?"  
   * Current infrastructure: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Willingness to add new type: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Decision Tree:**

* **IF** electric preferred → **PROBE** "What if battery limits range to 50 miles?"  
* **IF** infrastructure concern → **TEST** "What if we provided turnkey fuel solution?"  
* **IF** no preference → **PROBE** operational metrics that matter most

### **\[FR-02\] Autonomy Requirements**

**Hypothesis:** Level of autonomy affects adoption willingness

- [ ] Comfort with full autonomy: \_\_\_\_\_\_\_ (1-10 scale)   
- [ ] Remote pilot preference: \_\_\_\_\_\_\_ (1-10 scale)   
- [ ] Regulatory heartburn: \_\_\_\_\_\_\_ (1-10 scale)   
- [ ] On-site operator requirement: Y/N  
- [ ] Line-of-sight requirement: Y/N

**Interview Questions:**

1. "How do you feel about fully autonomous aerial operations?"  
   * Comfort level: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Concerns: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
2. "What level of human oversight would you require?"  
   * Minimum acceptable: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Decision Tree:**

* **IF** autonomy concern → **PROBE** "What specific scenarios worry you?"  
* **IF** requires human pilot → **TEST** "What if human could monitor 10 drones?"  
* **IF** fully comfortable → **PROBE** liability and insurance perspectives

### **\[FR-03\] Payload & Operations**

**Hypothesis:** Payload requirements vary significantly by use case

- [ ] Typical payload weight: \_\_\_\_\_\_\_ lbs   
- [ ] Typical payload value: $\_\_\_\_\_\_\_   
- [ ] Temperature control needs: \_\_\_\_\_\_\_   
- [ ] Security requirements: \_\_\_\_\_\_\_

**Interview Questions:**

1. "Describe your three most common remote delivery scenarios"  
   * Scenario 1: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Scenario 2: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Scenario 3: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
2. "What special handling requirements do your payloads have?"  
   * Requirements: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Decision Tree:**

* **IF** \<100 lbs typical → **PROBE** "Would you bundle multiple deliveries?"  
* **IF** high-value cargo → **PROBE** insurance, tracking, chain-of-custody needs  
* **IF** temperature sensitive → **TEST** acceptable temperature ranges, duration

### **\[FR-04\] Integration Requirements**

**Hypothesis:** Seamless integration with existing systems is critical

- [ ] Current TMS/WMS: \_\_\_\_\_\_\_   
- [ ] API requirements: \_\_\_\_\_\_\_   
- [ ] Reporting needs: \_\_\_\_\_\_\_

**Interview Questions:**

1. "How would this need to integrate with your existing systems?"  
   * Critical integrations: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Nice-to-have integrations: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
2. "What visibility do you need into aerial operations?"  
   * Real-time tracking: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Reporting requirements: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Decision Tree:**

* **IF** SAP/Oracle → **PROBE** specific modules, customization level  
* **IF** custom system → **TEST** "Would API access be sufficient?"  
* **IF** no system → **PROBE** current manual processes, Excel usage

## **\[RCT\] Adoption Timeline Discovery**

### **\[RCT-01\] Purchase Process Validation**

**Hypothesis:** Enterprise drone adoption follows standard technology procurement

- [ ] Typical evaluation period: \_\_\_\_\_\_\_ months   
- [ ] Pilot program requirement: Y/N   
- [ ] Proof of concept duration: \_\_\_\_\_\_\_ months

**Interview Questions:**

1. "How would you evaluate a solution like this?"  
   * Process: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Success criteria: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
2. "What would you need to see before full deployment?"  
   * Proof points: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Decision Tree:**

* **IF** requires pilot → **PROBE** scope, success metrics, timeline  
* **IF** fast adoption possible → **TEST** "What would accelerate purchase?"  
* **IF** very slow process → **PROBE** interim/rental options interest

## **\[AC\] Assumptions Testing**

### **\[AC-01\] Operational Assumptions**

**Test these assumptions explicitly:**

- [ ] Will accept new technology from existing vendor: Y/N \- Why? \_\_\_\_\_\_\_   
- [ ] Has budget for aerial solutions: $\_\_\_\_\_\_\_ annual   
- [ ] Regulatory comfort: \_\_\_\_\_\_\_ (1-10 scale)

**Interview Questions:**

1. "How do you view adding aerial capabilities from your truck vendor?"  
   * Perspective: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
2. "What concerns you most about drone operations?"  
   * Top concern: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
   * Dealbreakers: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Decision Tree:**

* **IF** vendor concern → **PROBE** "What if we partnered with drone specialist?"  
* **IF** budget constraint → **TEST** "What ROI would justify investment?"  
* **IF** regulatory worry → **PROBE** specific regulations, compliance needs

## **\[ASM\] Success Metrics Discovery**

### **\[ASM-01\] Value Measurement**

**Hypothesis:** Customers measure success through specific KPIs

□ Primary success metric: \_\_\_\_\_\_\_ 

□ Required ROI period: \_\_\_\_\_\_\_ months 

□ Cost baseline: $\_\_\_\_\_\_\_ per delivery currently

**Interview Questions:**

1. "How would you measure success of an aerial cargo program?"  
   * Metrics: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
2. "What ROI would justify this investment?"  
   * Requirement: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Decision Tree:**

* **IF** cost-focused → **PROBE** hidden costs in current solution  
* **IF** service-focused → **TEST** value of improved delivery times  
* **IF** no clear metrics → **PROBE** what they measure today

## **\[CIM\] Customer Interview Matrix**

### **Priority Interview Targets**

| Priority | Persona Type | Information Goals | Dependencies | Contact Strategy | Completed | Contact | Notes |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| **P0** | Current truck customer (remote facilities) | Validate remote delivery pain \[PV-01\], Payload requirements \[FR-03\] | Existing relationship | Through current AE |  |  |  |
| **P0** | Current truck customer (sustainability mandate) | Sustainability requirements \[PV-02\], ROI requirements \[ASM-01\] | Board-level mandate | Through CSM |  |  |  |
| **P1** | Supply Chain Director (Fortune 500\) | Purchase process \[RCT-01\], Integration needs \[FR-04\] | Enterprise scale | Industry conference (non-customer) |  |  |  |
| **P1** | Remote facility manager | Operational requirements \[FR-03\], Autonomy comfort \[FR-02\] | Direct user input | LinkedIn outreach |  |  |  |
| **P2** | Procurement officer | Budget availability \[AC-01\], Vendor requirements | Economic buyer | Referral from champion |  |  |  |
| **P2** | Sustainability officer | Environmental mandates \[PV-01\], Fuel preferences \[FR-01\] | ESG influence | Industry association |  |  |  |
| **P3** | Insurance provider | Liability perspectives \[AC-01\], Coverage requirements | Risk assessment | Partner introduction |  |  |  |
| **P3** | Competitor's customer | Unmet needs, switching triggers | Market gaps | Trade show |  |  |  |

### **Information Collection Checklist**

**Must Validate Before Proceeding:**

* \[ \] \>3 customers with \>$500K remote delivery spend  
* \[ \] Willingness to pay $500K-$1M per unit  
* \[ \] Comfort with autonomous operations  
* \[ \] 18-month ROI acceptable

**Must Understand Before Building:**

* \[ \] Payload range (weight, size, value)  
* \[ \] Range/duration requirements  
* \[ \] Integration requirements  
* \[ \] Regulatory constraints

**Nice to Know:**

* \[ \] Fuel preference rankings  
* \[ \] Competitive solutions evaluation  
* \[ \] Seasonal demand patterns  
* \[ \] Multi-site deployment interest

### **Additional Notes**

**Unanticipated learnings, new opportunities, surprises, anything not covered above:**
