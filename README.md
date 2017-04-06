# Switching-power-supply
DIY high power low voltage input power frount-end for inductive loads

Power distribution between Mosfets

According to the data sheet, when Vgs is below 9v, with the same gate charge, the coefficient between temperature and current is negative. This means most of current will try to pass through the hottest MOSFET and make it even hotter. This leads to breakdown within 10 switching cycle which is almost instant. To fix it, we need to keep gate charge high at maximum period of time. Recommend Vgs_p-p=15v. The coefficient is positive and grater when gate charge is higher. So that power is equally distributed.

One counter effect is gate ringing might be more significant.
