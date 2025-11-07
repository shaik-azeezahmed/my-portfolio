<script>
    import Layout from './shared/Layout.svelte'
    import Timeline from './shared/Timeline.svelte'

    let workTimeline = [
        {year: '2015', details: [
                        {title: 'Sigma infosolutions Pvt. Limited', monthStamp: 'Jun'}
                        ]
        },
        {year: '2018', details: [
                        {title: 'Infrrd.ai Pvt. Limited', monthStamp: 'Apr'}
                        ]
        },
        {year: '2025', details: [
                        {title: 'CES IT Pvt. Limited', monthStamp: 'Mar'}
                        ]
        },
        ]
</script>


<Layout gradientBg={true} hostComponent={'workHistory'}>
    <Timeline showMonthStamp={true} timelineEntries={workTimeline}></Timeline>
</Layout>