
/* New Things Every Day — Day 104 */
/* Calculates simple statistics from sample value */

function dailyLog104() {
    const values = [12, 25, 8, 41, 19];
    const total = values.reduce((sum, value) => sum + value, 0);
    const average = (total / values.length).toFixed(2);

    const report = {
        day: 104,
        timestamp: new Date().toISOString(),
        values,
        total,
        average
    };

    console.log("Day 104 Report:", report);
}

dailyLog104();
