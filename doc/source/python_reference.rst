=========
Reference
=========

This is the classes and functions reference of mne-python.

.. automodule:: mne
   :no-members:
   :no-inherited-members:

Classes reference
=================

.. autosummary::
   :toctree: generated/
   :template: class.rst

   mne.fiff.Raw
   mne.fiff.Evoked
   mne.Epochs
   mne.Covariance
   mne.SourceEstimate

Functions reference
===================

.. currentmodule:: mne

.. autosummary::
   :toctree: generated/
   :template: function.rst

   read_cov
   write_cov
   compute_covariance
   compute_raw_data_covariance
   label_time_courses
   read_label
   label_sign_flip
   write_label
   stc_to_label
   grow_labels
   read_bem_surfaces
   read_surface
   write_bem_surface
   read_source_spaces
   save_stc_as_volume
   morph_data
   read_stc
   write_stc
   read_w
   write_w
   read_proj
   write_proj
   compute_proj_epochs
   compute_proj_evoked
   read_selection
   fiff.pick_types
   fiff.pick_channels
   fiff.pick_types_evoked
   fiff.pick_channels_regexp
   fiff.pick_channels_forward
   fiff.pick_types_forward
   fiff.pick_channels_cov

.. automodule:: mne.minimum_norm
  :no-members:
  :no-inherited-members:

.. currentmodule:: mne.minimum_norm

.. autosummary::
   :toctree: generated/
   :template: function.rst

   read_inverse_operator
   write_inverse_operator
   make_inverse_operator
   apply_inverse
   apply_inverse_raw
   apply_inverse_epochs
   source_band_induced_power
   source_induced_power

.. automodule:: mne.mixed_norm
  :no-members:
  :no-inherited-members:

.. currentmodule:: mne.mixed_norm

.. autosummary::
   :toctree: generated/
   :template: function.rst

   mixed_norm

.. automodule:: mne.beamformer
  :no-members:
  :no-inherited-members:

.. currentmodule:: mne.beamformer

.. autosummary::
   :toctree: generated/
   :template: function.rst

   lcmv
   lcmv_epochs
   lcmv_raw

.. automodule:: mne.stats
 :no-members:
 :no-inherited-members:

.. currentmodule:: mne.stats

.. autosummary::
   :toctree: generated/
   :template: function.rst

   permutation_t_test
   permutation_cluster_test
   permutation_cluster_1samp_test
   fdr_correction
   bonferroni_correction

.. automodule:: mne.artifacts
 :no-members:
 :no-inherited-members:

.. currentmodule:: mne.artifacts

.. autosummary::
   :toctree: generated/
   :template: function.rst

   find_eog_events
   find_ecg_events

.. automodule:: mne.time_frequency
 :no-members:
 :no-inherited-members:

.. currentmodule:: mne.time_frequency

.. autosummary::
   :toctree: generated/
   :template: function.rst

   induced_power
   single_trial_power
   compute_raw_psd
   morlet
   yule_walker
   ar_raw
   iir_filter_raw

.. automodule:: mne.simulation
 :no-members:
 :no-inherited-members:

.. currentmodule:: mne.simulation

.. autosummary::
   :toctree: generated/
   :template: function.rst

   generate_evoked
   select_source_in_label
   generate_sparse_stc
