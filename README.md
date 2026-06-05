# AMG-GROUP-Medical-Analysis-Dashboard


Where Healthcare Meets Data Intelligence 🩺📊

At Alfa Medical Group, every single number represents a patient’s story. In my latest project, I transformed raw data into a secure, app-like Power BI experience.

I painted the interface in Red and Blue—because in healthcare, Blue and Red are all heartbeats. ❤️💙


🧹 Cleaning & Star Schema: Used Power Query to handle missing values, connecting transactional records (Fact_Samples) to lookup dimensions like branches, technicians, and units.

🔒 Dynamic Security (RLS) & Both Directions: Powered by USERPRINCIPALNAME(), the system locks data privacy based on the user's email. Configured Cross Filter Direction: Both for flawless filter propagation.

🧮 Advanced DAX Calculations: Developed complex measures using CALCULATE(), FILTER(), and SELECTEDVALUE() to ensure all KPIs compute accurately under tight security contexts.

📅 Continuous Calendar (Holidays & Weekends): Operations never stop. I customized a specialized Calender_Dim using DAX to track workloads, sales, and turn-around times (TAT) during weekends and national holidays.

🎨 Dynamic UI & App-Like Sign-In: Using logical validation in DAX, the welcome screen button dynamically changes based on who opens the report:

Branch Manager: Sign In to [Branch Name]

Unmapped View: AMG GROUP

Administrator: HI LAMIA ❤️💙!

🚀 Cross-Page Filter Syncing: Integrated hidden Sync Slicers with conditional navigation. Once the user clicks "Sign In", filters ripple across all dashboard pages instantly.

Healthcare data isn’t just numbers—it’s lives and timely decisions.
https://github.com/user-attachments/assets/9067d5b7-9be7-461b-9e2e-3166669e5764


