<h1>Automating AWS Reporting with Bash Scripting</h1>

<p>This repository contains a collection of Bash scripts designed to automate the process of generating and reporting on various aspects of AWS resources. These scripts aim to streamline common tasks such as fetching instance information, analyzing cost data, and monitoring resource utilization.</p>

<h2>Features</h2>
    <ul>
        <li><strong>Instance Information:</strong> Get detailed information about EC2 instances, including instance ID, type, state, and launch time.</li>
        <li><strong>Cost Analysis:</strong> Analyze AWS cost data to identify spending trends, cost-saving opportunities, and budget overruns.</li>
        <li><strong>Resource Utilization Monitoring:</strong> Monitor the utilization of various AWS resources such as EC2 instances, S3 buckets, and RDS databases.</li>
        <li><strong>Custom Reporting:</strong> Generate custom reports tailored to specific requirements or business needs.</li>
    </ul>

<h2>Requirements</h2>
    <ul>
        <li>Bash shell</li>
        <li>AWS CLI installed and configured with appropriate IAM permissions</li>
        <li>jq (for JSON parsing)</li>
        <li>sed, awk, grep (standard Linux/Unix utilities)</li>
    </ul>

<h2>Usage</h2>
    <ol>
        <li>Very First login into AWS virtual machine from Ubuntu. <a href="https://github.com/waliulrayhan/Automating-AWS-Reporting-with-Bash-Scripting/blob/main/SignIn%20AWS%20EC2%20From%20ubuntu">Try this</a></li>
        <li>Configure your favorite text editor. I prefer <a href="https://github.com/waliulrayhan/Automating-AWS-Reporting-with-Bash-Scripting/blob/main/VIM-Configuration">VIM</a></li>
        <li>Configure Your <a href="https://github.com/waliulrayhan/Automating-AWS-Reporting-with-Bash-Scripting/blob/main/AWS%20Configure">AWS Account</a></li>
        <li>Write the Shell Script <a href="https://github.com/waliulrayhan/Automating-AWS-Reporting-with-Bash-Scripting/blob/main/Shell%20Scripting">Code</a></li>
        <li>Follow the <a href="https://github.com/waliulrayhan/Automating-AWS-Reporting-with-Bash-Scripting/blob/main/Send%20Mail%20with%20SMTP">Steps</a> for sending mail using SMTP</li>
        <li>Finally, Run <a href="https://github.com/waliulrayhan/Automating-AWS-Reporting-with-Bash-Scripting/blob/main/Cron%20Job">cronjob</a> to automate the Shell Script for your day-to-day use</li>
    </ol>

<h2>Configuration</h2>
    <p>Before running the scripts, ensure that you have properly configured the AWS CLI with the necessary credentials and permissions. Additionally, some scripts may require customization to adapt to your specific AWS environment or reporting requirements. Review the scripts and modify any variables or parameters as needed.</p>

<h2>Contributing</h2>
    <p>Contributions to this repository are welcome! If you have ideas for additional features, improvements, or bug fixes, feel free to open an issue or submit a pull request.</p>

<h2>License</h2>
    <p>This project is licensed under the <a href="LICENSE">MIT License</a>, which means you are free to use, modify, and distribute the code for both commercial and non-commercial purposes.</p>

<h2>Disclaimer</h2>
    <p>While these scripts aim to automate and simplify common AWS reporting tasks, they come with no warranties or guarantees of accuracy or suitability for any specific purpose. Use them at your own risk, and always verify the results before making any critical decisions based on the generated reports.</p>
