<template>
    <div class="text-lg font-semibold text-left p-4">Report generator</div>
<body>
    <h2>Overall Database</h2>
    <table>
        <thead>
            <tr>
                <th style="width:60px">Priority number</th>
                <th>Ticket ID</th>
                <th>Ticket Status</th>
                <th>Closure Time</th>
                <th>Title</th>
                <th>Operator(Create TT)</th>
                <th>CreateTime(Create TT)</th>
                <th>Fault Level(Create TT)</th>
                <th>Alarm Type(Create TT)</th>
                <th>Alarm Name(Create TT)</th>
                <th>Fault Occurrence Time(Create TT_proccsrfaultoccurtime)</th>
                <th>SLA Status</th>
                <th>State(Process TT)</th>
                <th>Fault Recovery Time(Process TT_recoverytime)</th>
                <th>Fault Resolving Time(Process TT_faultresolvingtime)</th>
                <th>Fault last Occur Time (process)</th>
                <th>Fault Recovery Time(Process TT)</th>
                <th>CreateTime(Process TT)</th>
                <th>is Handle(Handle TT)</th>
                <th>AI analysis</th>
                <th>AI full analysis</th>
            </tr>
        </thead>
    </table>
    <footer>
        <p>Neural Nexus</p>
    </footer>
</body>
</template>

<script setup>

</script>

<style scoped>
table{
    width: 100%;
    margin-top: 20px;
    border-color: skyblue;
    color: skyblue;
    table-layout: fixed;

    
}
tr{
    border-color: skyblue;
    color: skyblue;
    border-style: solid;
    border-width: 1px;
}
th{
    border-color: skyblue;
    color: skyblue;
    border-style: solid;
    border-width: 1px;
    width: 200px;
    height: auto;
}
</style>
