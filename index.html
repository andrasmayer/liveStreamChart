<html>
<head>
<script src="https://www.chartjs.org/dist/2.8.0/Chart.min.js"></script>
<script>
function draw(data){
		
		 config = {
			type: 'line',
			data: {
				labels: data.labels,
				datasets: [{
					label: 'My First dataset',
					backgroundColor: 'red',
					borderColor: 'red',
					data: data.dataset,
					fill: false,
				}]
			},
			options: {
				
				 animation: {
        duration: 0
    },
				
				
				
				responsive: true,
				title: {
					display: true,
					text: 'Sample Data'
				},
				tooltips: {
					mode: 'index',
					intersect: false,
				},
				hover: {
					mode: 'nearest',
					intersect: true
				},
				scales: {
					xAxes: [{
						display: true,
						scaleLabel: {
							display: true,
							labelString: 'Time'
						}
					}],
					yAxes: [{
						display: true,
						scaleLabel: {
							display: true,
							labelString: 'Value'
						}
					}]
				}
			}
		};


var ctx = document.getElementById('canvas').getContext('2d');
window.myLine = new Chart(ctx, config);

}
</script>
</head>
<body>


<div style="width:1200px;height:400px;">
<canvas id="canvas" ></canvas>
<div>  



<script>
data={dataset:[],labels:[]};																		//Empty Dataset for start

timer	=	1000;																					//Refresh time basely 1 second
secondsTillReset	=	10;

setInterval(function(){

date	=	new Date();
hour	=	date.getHours();	if(hour<10){	hour=	'0'+hour;	}
minutes	=	date.getMinutes();	if(minutes<10){	minutes=	'0'+minutes;	}
seconds	=	date.getSeconds();	if(seconds<10){	seconds=	'0'+seconds;	}
time	=	hour+':'+minutes+':'+seconds;															//Cheate H:i:s

num=Math.random();
num2=Math.random();

if(data.dataset.length>secondsTillReset){		data.dataset.shift(); 	data.labels.shift();	}	//Push array with first till have 10 elemens
data.dataset.push(Math.round(num*10)*Math.round(num2*100)*Math.round(num2*10));						//Then remove the first and add a new
data.labels.push(time);

draw(data);																							//Draw / Redraw the chart at the end of the loop					
	
}, timer);
</script>
</body>
</html>