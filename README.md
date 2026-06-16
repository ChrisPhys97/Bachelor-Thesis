<h2>Overview</h2>
<div style="text-align: justify; text-justify: inter-word; font-size: 18px;">
<p>
  This repository contains three Jupyter notebooks presenting the results of the
  <strong>shear-dominant sensitivity experiment</strong> performed with the MISU MIT Cloud and Aerosol (MIMICA) Large Eddy Simulation (LES) model.
</p>

<p>
  The first notebook focuses on the analysis and visualization of
  coherent turbulent structures, while the second examines
  the mean structure of the atmospheric boundary layer (ABL) through
  vertically averaged thermodynamic and turbulence profiles. The energy spectrum analysis presented in the third notebook was developed after the completion of my     Bachelor's thesis as an extension of the original work. The objective was to further investigate the characteristic scales of turbulent structures within the        atmospheric boundary layer (ABL) using spectral methods. All notebooks
  include a brief discussion of the main results and their physical
  interpretation.
</p>

<p>
  These simulations were carried out as part of my BSc thesis under the
  supervision of <strong>Assistant Professor Georgia Sotiropoulou</strong>.
  The study investigates the dynamics of the marine stratocumulus (ABL) under shear-dominated conditions using case studies based on on-site data gatherd during the DYCOMS-II campaign off the coast of California (Akerman et all., 2009).
</p>

<p>
  In addition to the shear-dominant experiment presented here, a second
  sensitivity test was conducted for a
  <strong>buoyancy-intensified marine stratocumulus ABL</strong>, allowing for
  a comparison between mechanically and buoyancy-driven turbulence regimes.
</p>

<p>
  For the energy spectrum, the methodology is based on applying a two-dimensional Fast Fourier Transform (FFT) to horizontal slices of the velocity fluctuations.      The resulting two-dimensional energy spectrum is converted into a one-dimensional radial spectrum by averaging over concentric wavenumber shells. The                implementation was validated by comparing the direct variance of the velocity fluctuations with the variance recovered from both the two-dimensional and one-        dimensional spectra, ensuring energy conservation. The dominant turbulent length scale is estimated from the peak wavenumber through

  $L_{\mathrm{peak}}=\frac{2\pi}{k_{\mathrm{peak}}},$

  allowing a direct comparison between the spectral characteristics and the coherent turbulent structures observed in the flow fields. The analysis was performed      for several vertical levels within the ABL, providing insight into the evolution of the characteristic eddy sizes throughout the mixed layer and the cloud layer
</p>

</div>
