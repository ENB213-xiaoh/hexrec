hexrec.formats.intel.Record
===========================

.. currentmodule:: hexrec.formats.intel

.. autoclass:: Record

   
   .. automethod:: __init__

   
   .. rubric:: Methods

   .. autosummary::
   
      ~Record.__init__
      ~Record.build_data
      ~Record.build_end_of_file
      ~Record.build_extended_linear_address
      ~Record.build_extended_segment_address
      ~Record.build_standalone
      ~Record.build_start_linear_address
      ~Record.build_start_segment_address
      ~Record.check
      ~Record.check_sequence
      ~Record.compute_checksum
      ~Record.compute_count
      ~Record.get_metadata
      ~Record.is_data
      ~Record.load_blocks
      ~Record.load_memory
      ~Record.load_records
      ~Record.marshal
      ~Record.overlaps
      ~Record.parse_record
      ~Record.read_blocks
      ~Record.read_memory
      ~Record.read_records
      ~Record.readdress
      ~Record.save_blocks
      ~Record.save_memory
      ~Record.save_records
      ~Record.split
      ~Record.terminate
      ~Record.unmarshal
      ~Record.update_checksum
      ~Record.update_count
      ~Record.write_blocks
      ~Record.write_memory
      ~Record.write_records
   
   

   
   
   .. rubric:: Attributes

   .. autosummary::
   
      ~Record.EXTENSIONS
      ~Record.LINE_SEP
      ~Record.REGEX
      ~Record.address
      ~Record.checksum
      ~Record.count
      ~Record.data
      ~Record.tag
   
   