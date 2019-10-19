# Rust-mod
pub mod order {     pub mod order_rcvd {         pub fn one() {         println!("Order is recieved");         }         pub mod order_in_process {            pub fn two() {             println!("Order is in process");             }         }     } } fn main() { crate::order::order_rcvd::one(); crate::order::order_rcvd::order_in_process::two(); }
