Inspired by https://github.com/ssebastianmag/hydrogen-wavefunctions

Both Jupyter Notebooks firstly calculate the $R$, $\Theta$ and $\Phi$ parts of the Hydrogen wavefunction $\Psi_{nml}$.

The $R(r)$ function is defined as: 

$R(r) = (\frac{2}{na})^ {3/2} \frac{(n - l - 1)!}{2n(n + l)!} (\frac{2r}{na})^l e^{\frac{-r}{na}}    r^{-(2l + 1)} \frac{e^r}{(n - l - 1)!} \frac{2}{na} \frac{d^{(n - l - 1)}}{d^{(n - l - 1)} r} (\frac{2r}{na}^{(2l + 1)+(n - l - 1)} e^{-\frac{2r}{na}})   $

The $\Theta(\theta)$ function is defined as:

$\Theta(\theta) = (-1)^m (1-\cos^2\theta)^{m/2} \frac{d^m}{d\cos^m\theta}(\frac{1}{2^l l!} \frac{d^l}{d\cos^l\theta} (\cos^2\theta -1)^l)    $

The $\Phi(\phi)$ function is defined as:

$\Phi(\phi) = \sqrt{\frac{2l+1}{4\pi}\frac{(l-m)!}{(l+m)!}} e^{im\phi}$


# **Images:**


3D Wavefunction of $\Psi_{210}$:

![image](https://github.com/fran2402/3DHydrogenWavefunction/assets/83206710/8ebb2dc8-7ab2-479a-baad-8c1a5e86149b)

3D Wavefunction of $\Psi_{320}$:

![image](https://github.com/fran2402/3DHydrogenWavefunction/assets/83206710/394ce388-f381-4597-a4a5-a58ab4119425)

3D Wavefunction of $\Psi_{532}$:

![image](https://github.com/fran2402/3DHydrogenWavefunction/assets/83206710/87f29659-930d-4b96-8015-35a8d04a6b98)
