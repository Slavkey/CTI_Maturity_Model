# CTI_Maturity_Model


## What is it? Who is it for? What's the purpose?

**Cyber Threat Intelligence Maturity Model (CTI-MM)** is a theoretical representation of CTI organizational development. The development in this case is meant as a process during which standards, baselines, and procedures are created, shared across the organization, and matured (including testing and improving). The term "maturity" relates to the degree of professional development of services and products, formality and optimization of processes, from ad hoc practices, to formally defined steps, managed result metrics, and active optimization of the processes.
Just like Capability Maturity Model Integrated (https://en.wikipedia.org/wiki/Capability_Maturity_Model_Integration) can be used to "(...) guide process improvement across a project, division, or entire organizations", the CTI-MM can be used by all of you, for whom the constant development and improvement of intel services and products is important.

Overall, my intent when creating a CTI-MM was to help intel Subject Matter Experts (SMEs), their key stakeholders, and business owners, design, develop, and mature CTI capabilities in a structured and systemic way. Therefore this model is more meant to drive the CTI development than provide a formal assessment tool (like CREST CTI Maturity Assessment Tools: https://www.crest-approved.org/cyber-threat-intelligence-maturity-assessment-tools/).
Since budgets are always too small, and the area of CTI operations is always so vast, the most important ideas behind this model were to:
<ul>
  <li> Create a detailed vision of how CTI and its capabilities can be developed and matured in organizations</li>
  <li> Provide a handy (I hope) and comprehensive tool for self-assessment of current CTI capabilities and processes</li>
  <li> Help CTI SMEs in the design and development of intel programs that best fit the needs of their organizations or customers</li>
</ul>
Hopefully, thanks to that approach CTI SMEs will know what should they focus on in the short and long run. 

## How was it designed and why?
Although the inspiration for my work was CMM used by software development organizations, I based most of the details of CTI-MM on my personal experience. While working in (threat) intelligence in different setups and for various stakeholders, I experienced how complex it is to develop intelligence capabilities and how many factors contribute to the overall success. 
I divided the maturity levels based on the types of intelligence (Strategic, Operational, Tactical) and phases of the intelligence cycle (https://en.wikipedia.org/wiki/Intelligence_cycle).
Below is a high-level overview of how the CTI program evolves on each maturity level. 

![image](https://github.com/Slavkey/CTI_Maturity_Model/assets/141276405/9fe09ddc-3bf0-4455-9091-e1a567c3ca28)

The most important in the model are "controls". Each of them represents a granular capability that can be found / observed in CTI at a chosen maturity level (see picture below).
![image](https://github.com/Slavkey/CTI_Maturity_Model/assets/141276405/ba93a474-366f-413c-8e46-61bdb3254400)
Because it's not possible to have a fully professional Cyber Threat Intelligence in an organization with an overall low maturity level, all those capabilities are logically and meaningfully tied in the model. Based on that, you can identify/track how they should evolve and grow. With this, you can plan your next steps in a crawl-walk-run approach.
Of course, the model is not meant to be the only way of doing things but should serve as a guide for how everything that influences your intel capabilities can be done. Although the plan was designed specifically for CTI, I think other organizations with "Intelligence" in names can find there something useful too. 

## How to use it?
  **If you start your program from scratch:**
<ol>
    <li>Take a look at the whole model from a macro-perspective and decide what maturity level satisfies your needs - remember those needs are established NOT by CTI but by the organization or business needs.</li>
    <li>Identify which controls/capabilities are already present in your environment.</li>
    <li>Identify controls you need to focus on in the first place.</li>
    <li>Identify, describe processes, technologies, and people (PTP) you need to achieve chosen capabilities (as detailed as can be).</li>
    <li>Prepare a development plan that will present details of how you want to professionalize your CTI.</li>
    <li>Track and monitor the development process by using periodical self-assessments, the power of pivot tables and BI dashboards. ;)</li>
</ol>

  **If you want to find potential for further development:**
<ol>
  <li>Identify which controls/capabilities are already present in your environment.</li>
  <li>Assess the current maturity level.</li>
  <li>Prepare development plan and identify priorities.</li>
  <li>Identify, describe processes, technologies, and people you need to achieve chosen capabilities (as detailed as can be).</li>
  <li>Track and monitor the development process.</li>
</ol>

## Technical Remarks
_In the excel file, you will find examples of PTP for level 1 only. The rest is a work in progress. Although I think those, because of their granularity, will differ with organizations, their business needs, constraints, budgets, etc._ 

## PS
I hope by sharing this repo CTI community will find a useful tool, that will enable a less formal but still orderly way of assessing and developing intel programs. 
The repo is a 'work in progress'. I'd like to invite you all to develop it and make the model more useful in our work. 
For those of you who start working on CTI in your own organizations, I hope this will greatly increase your awareness of how complex this is. Believe me, establishing CTI is not only about implementing feeds or even buying TIP ;)




