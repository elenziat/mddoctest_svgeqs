# Test
For the minimal examples the test system is a simple one-mass-oscillator described by

<p align="center"><img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/cc6824dc09cabeaff44dffe078fa4051.svg?invert_in_darkmode" align=middle width=272.43645pt height=95.16181784999999pt/></p>

The nominal parameters are <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/a08aa3f720eb59983ccb69372a8b620d.svg?invert_in_darkmode" align=middle width=44.56994024999999pt height=21.18721440000001pt/>, <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/7474a88176e3b7318768ff82da2d4a2c.svg?invert_in_darkmode" align=middle width=46.91201294999998pt height=22.831056599999986pt/> and <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/982ad20eaa8b08dbe1bd927db94f4959.svg?invert_in_darkmode" align=middle width=61.90827224999998pt height=21.18721440000001pt/>.
For the robust design the parameters <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/0e51a2dede42189d77627c4d742822c3.svg?invert_in_darkmode" align=middle width=14.433101099999991pt height=14.15524440000002pt/> and <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/2103f85b8b1477f430fc407cad462224.svg?invert_in_darkmode" align=middle width=8.55596444999999pt height=22.831056599999986pt/> are assumed to be uncertain, given by

<p align="center"><img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/72a72220711931d569f1f838a3132f6b.svg?invert_in_darkmode" align=middle width=98.4512991pt height=41.09589pt/></p>



#### Additional objective term

With the code above, all solutions for <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode" align=middle width=12.60847334999999pt height=22.465723500000017pt/> within the interval <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/13233b491e745213e4f4d891faadb905.svg?invert_in_darkmode" align=middle width=96.80389784999998pt height=24.65753399999998pt/> are "equally good" solution of the feasibility problem.
The exact value found depends on the initial value and the optimizer used.
(You could change the start value to <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/cd9981ea0a7b60c42e599e40874e4798.svg?invert_in_darkmode" align=middle width=45.66227159999998pt height=21.18721440000001pt/> to observe a difference.)

This means there exists a certain degree of freedom which can be used for other purposes.
The following code finds the controller among the feasible ones with the smallest norm of the feedback matrix.
In this case, it is just the <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode" align=middle width=12.60847334999999pt height=22.465723500000017pt/> with the smallest absolute value, i.e. the unique solution now is <img src="https://raw.githubusercontent.com/pvogt09/gammasyn/master/docs/svgs/5e6cdf4bc23893eaed8ff5077bdd34de.svg?invert_in_darkmode" align=middle width=91.61394659999998pt height=22.465723500000017pt/>.
