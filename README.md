import React from "react";
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { FaLeaf, FaHandsHelping, FaHeartbeat } from "react-icons/fa";

export default function Home() {
  return (
    <div className="min-h-screen bg-green-50 p-4">
      <header className="text-center py-6 bg-green-600 text-white text-3xl font-bold rounded-lg">
        Asma's Acupuncture Home
      </header>
      
      <section className="text-center py-10">
        <h2 className="text-2xl font-semibold mb-4">Welcome to Holistic Healing</h2>
        <p className="text-gray-700 max-w-2xl mx-auto">
          Experience the ancient art of acupuncture to restore balance and well-being in your life.
        </p>
        <Button className="mt-4 bg-green-500 hover:bg-green-700">Book an Appointment</Button>
      </section>
      
      <section className="grid md:grid-cols-3 gap-6 py-10">
        <Card>
          <CardContent className="p-6 text-center">
            <FaLeaf className="text-green-600 text-5xl mx-auto mb-4" />
            <h3 className="text-xl font-semibold">Natural Healing</h3>
            <p className="text-gray-600">Our acupuncture treatments harness the body's natural energy to promote healing.</p>
          </CardContent>
        </Card>
        <Card>
          <CardContent className="p-6 text-center">
            <FaHandsHelping className="text-green-600 text-5xl mx-auto mb-4" />
            <h3 className="text-xl font-semibold">Personalized Care</h3>
            <p className="text-gray-600">Each treatment plan is customized to meet your unique health needs.</p>
          </CardContent>
        </Card>
        <Card>
          <CardContent className="p-6 text-center">
            <FaHeartbeat className="text-green-600 text-5xl mx-auto mb-4" />
            <h3 className="text-xl font-semibold">Holistic Wellness</h3>
            <p className="text-gray-600">Balance your mind, body, and soul with our expert acupuncture techniques.</p>
          </CardContent>
        </Card>
      </section>
      
      <footer className="text-center py-6 bg-green-600 text-white rounded-lg mt-10">
        &copy; 2025 Asma's Acupuncture Home. All Rights Reserved.
      </footer>
    </div>
  );
}
