<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h2>Teamwork Documentation - Edge AI Dashcam Project</h2>

<h3>Team Members</h3>

<table border="1" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr>
            <th>Member</th>
            <th>Role</th>
            <th>Primary Phases</th>
            <th>GitHub Handle</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>Member 1</strong></td>
            <td>Model Specialist</td>
            <td>Phase 1, Phase 2</td>
            <td>@member1</td>
        </tr>
        <tr>
            <td><strong>Member 2</strong></td>
            <td>Pipeline Developer</td>
            <td>Phase 3, Phase 5</td>
            <td>@member2</td>
        </tr>
        <tr>
            <td><strong>Member 3</strong></td>
            <td>System Integrator</td>
            <td>Phase 4, Phase 5</td>
            <td>@member3</td>
        </tr>
    </tbody>
</table>

<h2>Phase Assignments & Responsibilities</h2>

<h3>Phase 1: Environment Setup & Model Selection (Week 1)</h3>
<p><strong>Lead</strong>: Member 1<br>
<strong>Support</strong>: Member 2, Member 3</p>

<h4>Tasks</h4>
<ul>
    <li><strong>Member 1</strong>: Install RPi OS, setup virtual environment, create requirements.txt</li>
    <li><strong>Member 2</strong>: Research & benchmark 3 detection models (MobileNet-SSD, YOLOv5s, etc.)</li>
    <li><strong>Member 3</strong>: Setup Git repository, create project structure, initial README</li>
</ul>

<p><strong>Deadline</strong>: End of Week 1<br>
<strong>Review Meeting</strong>: Week 1 Friday</p>

<h3>Phase 2: Model Optimization (Week 2)</h3>
<p><strong>Lead</strong>: Member 1<br>
<strong>Support</strong>: Member 2</p>

<h4>Tasks</h4>
<ul>
    <li><strong>Member 1</strong>: Convert model to TFLite/ONNX, quantization, edge benchmarking</li>
    <li><strong>Member 1</strong>: Create models/ directory with optimized model</li>
    <li><strong>Member 2</strong>: Test model inference speed, document FPS results</li>
    <li><strong>Member 3</strong>: Update README with model selection justification</li>
</ul>

<p><strong>Deadline</strong>: End of Week 2<br>
<strong>Review Meeting</strong>: Week 2 Friday</p>

<h3>Phase 3: Video Pipeline Development (Week 3)</h3>
<p><strong>Lead</strong>: Member 2<br>
<strong>Support</strong>: Member 1</p>

<h4>Tasks</h4>
<ul>
    <li><strong>Member 2</strong>: Build OpenCV camera pipeline (src/pipeline.py)</li>
    <li><strong>Member 2</strong>: Integrate model inference (src/detector.py)</li>
    <li><strong>Member 1</strong>: Debug model integration issues</li>
    <li><strong>Member 3</strong>: Setup logging directory structure</li>
</ul>

<p><strong>Deadline</strong>: End of Week 3<br>
<strong>Review Meeting</strong>: Week 3 Friday</p>

<h3>Phase 4: Logging & Alert System (Week 4)</h3>
<p><strong>Lead</strong>: Member 3<br>
<strong>Support</strong>: Member 2</p>

<h4>Tasks</h4>
<ul>
    <li><strong>Member 3</strong>: Implement timestamped logging (src/logger.py)</li>
    <li><strong>Member 3</strong>: Add anomaly clip saving functionality</li>
    <li><strong>Member 2</strong>: Performance optimization (&ge;5 FPS)</li>
    <li><strong>Member 1</strong>: Test detection accuracy, reduce false positives</li>
</ul>

<p><strong>Deadline</strong>: End of Week 4<br>
<strong>Review Meeting</strong>: Week 4 Friday</p>

<h3>Phase 5: Testing & Demo (Week 5)</h3>
<p><strong>Leads</strong>: All Members</p>

<h4>Tasks</h4>
<ul>
    <li><strong>Member 2</strong>: Record demo video, create presentation</li>
    <li><strong>Member 3</strong>: Write final report (model choice, optimization, performance)</li>
    <li><strong>Member 1</strong>: Final testing under varying conditions</li>
    <li><strong>All</strong>: Code review, documentation cleanup</li>
</ul>

<p><strong>Deadline</strong>: End of Week 5<br>
<strong>Final Demo</strong>: Week 5</p>

<h2>Weekly Workflow</h2>
<ul>
    <li><strong>Monday</strong>: Individual task work</li>
    <li><strong>Wednesday</strong>: Merge requests & peer review</li>
    <li><strong>Friday</strong>: Phase review meeting (30 mins)</li>
    <li><strong>Daily</strong>: Slack/Discord updates</li>
</ul>

<h2>Communication Guidelines</h2>
<ul>
    <li><strong>Daily Updates</strong>: Slack channel #daily-standup</li>
    <li><strong>Code</strong>: GitHub PRs with clear descriptions</li>
    <li><strong>Issues</strong>: GitHub Issues tracker</li>
    <li><strong>Meetings</strong>: Friday 5 PM IST (30 mins)</li>
</ul>

<h2>Success Metrics</h2>
<ul>
    <li><strong>Phase Completion</strong>: All deliverables by phase deadlines</li>
    <li><strong>Code Quality</strong>: PRs approved by 2 team members</li>
    <li><strong>Performance</strong>: &ge;5 FPS achieved</li>
    <li><strong>Documentation</strong>: Complete README and reports</li>
</ul>

<h2>Emergency Protocol</h2>
<ol>
    <li>If a member falls behind:</li>
    <li>Notify team immediately</li>
    <li>Reassign critical tasks</li>
    <li>Extend deadline only with instructor approval</li>
</ol>

</body>
</html>
